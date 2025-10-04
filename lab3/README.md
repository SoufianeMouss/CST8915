# LAB 3 CST8915

### Video
https://www.awesomescreenshot.com/video/44918857?key=aabebfcc1473536ac65996f0af41c217

### Challenges
 1. The first one is the environment inside the YAML file for the Front view, I struggled to make the connection between the front and product service, because there was a slash at the end of the URL "/"
 2. I spent a lot of time trying to make Python work with the front end, I was getting a 404 when I inspect the element in the browser. at the end the issue was related to CORS. I needed to add this code below in order for Azure to let the connection between the two services
 ```
# Read allowed origins from environment (comma-separated string)
ALLOWED_ORIGINS = os.getenv("ALLOWED_ORIGINS", "*").split(",")

app.add_middleware(
    CORSMiddleware,
    allow_origins=ALLOWED_ORIGINS,   # list of allowed origins
    allow_credentials=True,
    allow_methods=["*"],             # GET, POST, OPTIONS, etc.
    allow_headers=["*"],
)
 ```
PS : That's what led me to submit late
### Deploying microservices on Azure Web App
One of the main reasons is to use each service separately, and the most important thing is the scaling
### Importance for environment variables in a cloud environment
Environment variables are important in the cloud because they let us separate configuration and secrets from the code, in line with the 12-Factor App principles for building cloud-native applications.
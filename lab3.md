## What challenges did you encounter when configuring environment variables in the GitHub Actions workflow?
- Not Applicable, as I did not deploy the store-front on a static web app service due azure account limitations (explained in the demo video).
  
## How does deploying microservices on Azure Web App Service differ from running them locally?
- On the Web App Service there's no configurations like installing libraries and running the service. this is handled automatically in the brakcground
- No need to create a .env file for storing the variable environment, all is handled by the managed service.
- Azure uses managed networking.

## Why is it important to use environment variables for configurations in a cloud environment?
- Keep code and config separate.
- Update configs without redeploying.
- Portable and cloud-native (12-Factor App).

## Demo video

[https://youtu.be/x6bb8ocsTw4](https://youtu.be/x6bb8ocsTw4)

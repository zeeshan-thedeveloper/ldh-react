# About ldh-react
This is an open npm package that will be used by developers to consume the services provided by the local-database-hosting service

# How to use it?
Follow the steps.

1. Go to our official [web-portal](https://central-api-layer-73ctvrbrm-zeeshan-thedeveloper.vercel.app)
2. Login/Sign up as developer.
    
![image](https://user-images.githubusercontent.com/66442918/183244776-b8b7f314-0424-4c4e-aae8-e37d3d4ce7db.png)

3. Then go to option: "Generate token " and select the host and validation time. And hit the generate button. For futher information about how to get connected to hosts please visite our [official integration](https://central-api-layer-73ctvrbrm-zeeshan-thedeveloper.vercel.app/Integration)
![Unsaved Image 1](https://user-images.githubusercontent.com/66442918/183245118-baa3d4c9-fed0-4a89-98b0-39d9b7d3f297.jpg)

4. After that you will get the following screen. Just hit the buttons and copy the accessToken, accessUrl and Secret key and store it somewhere in your application.

![Unsaved Image 1](https://user-images.githubusercontent.com/66442918/183245173-19b82fb8-d6ce-4524-b0cd-60e932ee89cf.jpg)

5. You might store them in .env file or direct in variables.

![image](https://user-images.githubusercontent.com/66442918/183245210-3d6dfd61-a984-4f06-9628-ecd715863196.png)

6. After that in your react project run the command :  `npm install ldh-react`
7. Now import `import {LocalDatabaseHosting} from 'ldh-react'`
8. Use the above stored values to configure an object of ldh.

![image](https://user-images.githubusercontent.com/66442918/183245346-a1473fa7-2232-41c4-bb65-6af3ebda51a9.png)

9. Then use async and wait to execute your queries with the following method.
![image](https://user-images.githubusercontent.com/66442918/183245418-16539d4b-4ec2-4bc3-8901-af303191464c.png)

10. Hurrah ... you have accessed the remote local database.

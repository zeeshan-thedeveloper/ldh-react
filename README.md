# About ldh-react
This is an open npm package that will be used by developers to consume the services provided by the local-database-hosting service

# How to use it?
Follow the steps.

1. Go to our official [web-portal](https://central-api-layer-73ctvrbrm-zeeshan-thedeveloper.vercel.app)
2. Login/Sign up as developer.
    
![image](https://user-images.githubusercontent.com/66442918/191009605-20a12cd8-b824-478a-8325-c40c9d8932a6.png)

3. Then go to option: "Generate token " and select the host and validation time. And hit the generate button. For futher information about how to get connected to hosts please visite our [official integration](https://central-api-layer-73ctvrbrm-zeeshan-thedeveloper.vercel.app/Integration)

![image](https://user-images.githubusercontent.com/66442918/191009773-9c818319-8021-474e-95dc-c82e64217898.png)

4. After that you will get the following screen. Just hit the buttons and copy the accessToken, accessUrl and Secret key and store it somewhere in your application.

![image](https://user-images.githubusercontent.com/66442918/191009950-d9ef5203-33d7-4fed-9357-49412a2e2e7b.png)

5. You might store them in .env file or direct in variables.

![image](https://user-images.githubusercontent.com/66442918/183245210-3d6dfd61-a984-4f06-9628-ecd715863196.png)

6. After that in your react project run the command :  `npm install ldh-react`
7. Now import `import {LocalDatabaseHosting} from 'ldh-react'`
8. Use the above stored values to configure an object of ldh.

![image](https://user-images.githubusercontent.com/66442918/183245346-a1473fa7-2232-41c4-bb65-6af3ebda51a9.png)

9. Then use async and wait to execute your queries with the following method.
![image](https://user-images.githubusercontent.com/66442918/183245418-16539d4b-4ec2-4bc3-8901-af303191464c.png)

10. Hurrah ... you have accessed the remote local database.

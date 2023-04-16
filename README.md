# CI-CD-pipline


I'm going to use "AWS Codepipeline"

![image](https://user-images.githubusercontent.com/51129966/232261268-5549e39a-bc4f-433a-8151-163340ea349b.png)


It is now time to set up a pipeline

![image](https://user-images.githubusercontent.com/51129966/232261283-a65bf739-db4f-4255-9861-2d2be197edd3.png)

Give a project name and select a new role

![image](https://user-images.githubusercontent.com/51129966/232261306-fb73761c-4690-457c-8664-236cb21af87e.png)

It's time to add your source code. In my case, I'm using GitHub version 2.

![image](https://user-images.githubusercontent.com/51129966/232261336-4be772c5-2cc9-4db0-b4ae-6a39a4bec2a7.png)

"Since my website doesn't need to be built, I have skipped the build function and instead used the CodeDeploy function. I have selected S3 as the deployment destination

![image](https://user-images.githubusercontent.com/51129966/232261355-774a055e-a607-44f8-b07c-96b6303a0c53.png)


Whenever I modify my source code, the changes are automatically reflected on my website thanks to my pipeline.

![image](https://user-images.githubusercontent.com/51129966/232261404-68b84163-2f7d-41c2-ab2c-038399f89ea9.png)

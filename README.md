## 🚀 About Me
I'm a junior DevOps engineer with some expertise in BackEnd development using Java and Node.js; scripting skills with Python, Bash and JavaScript; besides CI/CD and cloud knowledge of AWS and Azure DevOps tools ...

![Logo](https://e1.pxfuel.com/desktop-wallpaper/541/577/desktop-wallpaper-fantastic-backgrounds.jpg)
![linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![mysql](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white)
![aws](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![azuredevops](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)

## 🔗 Portfolio
[![portfolio](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RecursiveDeveloper)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jhoan-jesus-ortiz-sandoval-a66152198/)

# AWS ECR & ECS deploy with GitHub actions

Deploy a simple GitHub actions CI/CD Workflow into AWS ECR and ECS services. It consists of a Dockerfile to build a Nginx image where an index.html file will be stored in order to display a static web page using ECS as the server by proving a task-definition.json file with all the necessary configurations and ECR as the image registry once the image has been built and pushed.

![image](https://raw.githubusercontent.com/RecursiveDeveloper/static-media-content/main/Demo_ecs-ecr.drawio.png)

## Tech Stack 

- **Client:** ---
- **Server:** ECR, ECS
- **Database:** ---
- **Cloud provider:** AWS
- **Tools:** GitHub Actions

## Installation

1. Check the repository settings and look for Secrets and Variables option. Set up those variables according to your needs. They have to match with the name of the aws services you create.
2. Check the repository settings and look for Environment option. Set up those variables according to your needs. They have to match with the name of the aws services you create. 
2. Create your own ECR repository [Creating an Amazon ECR private repository
](https://docs.aws.amazon.com/AmazonECR/latest/userguide/repository-create.html)
3. Create your own ECS cluster, task definition skeleton file and ECS service where tasks will be orchestrated  
    - Guide 1: [How to create an Amazon ECS Linux task for the Fargate launch type](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/getting-started-fargate.html)
    - Guide 2: [Deploying to Amazon Elastic Container Service
](https://docs.github.com/es/actions/use-cases-and-examples/deploying/deploying-to-amazon-elastic-container-service)

## Deployment

To deploy this project run

1. Go to Actions option
2. Select Workflow to deploy to Amazon ECS
3. Click on Run Workflow and be sure to be in the main branch
4. That's it!

## Authors

- [@RecursiveDeveloper](https://github.com/RecursiveDeveloper)


## License

[MIT](https://choosealicense.com/licenses/mit/)

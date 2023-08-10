
# AWS-CFTs

This repository contains Cloudformation templates written in YAML for creating and deploying various services.



## Authors

- [@Cap10Coderman](https://github.com/Cap10Coderman)


## Deployment

To clone this project to local.. run

```bash
  git clone https://github.com/Cap10Coderman/AWS-CFTs.git
```


## Creating Stack in Cloudformation.

Make sure the IAM User creating this stack has necessory permission to perform the action.

### Creating the stack
```bash
aws cloudformation create-stack \
--stack-name (Stack_Name) \
--template-body file://(filename) \
--region ap-south-1 \
--tags Key=user,Value=coderman Key=project,Value=research \
--capabilities CAPABILITY_IAM
```

### Updating the stack
```bash
aws cloudformation update-stack \
--stack-name (Stack_Name) \
--template-body file://(filename) \
--region ap-south-1 \
--tags Key=user,Value=coderman Key=project,Value=research \
--capabilities CAPABILITY_IAM
``` 
### Delete the stack
```bash
aws cloudformation delete-stack \
--stack-name (Stack_Name) \
--region ap-south-1 \
```

# Hi, I'm Cap10Coderman! 👋


## 🚀 About Me
I'm a Security Engineer and a devoloper...


## 🛠 Skills
AWS Cloud Security, Cost Analysis, Configuring and patching...


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://unnikrishnansi.wixsite.com/unnikrishnan-si)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/unni-krishnan-s-i-69b7631a4)



## Are you intersted in knowing me..
👩‍💻 I'm currently working on AWS..

🧠 I'm currently learning CyberSecurity.

👯‍♀️ I'm looking to collaborate on CyberSecurity Projects.

📫 Reach me at https://unnikrishnansi.wixsite.com/unnikrishnan-si

😄 Pronouns

⚡️ Fun fact


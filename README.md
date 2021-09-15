## ci-cd-assignment

##  README

### Clone the Github Repository

Use the below clone command 
```bash
git clone https://github.com/Shashikant-15/SOLID_Principle_Assignment/.git
```
 ### CI/CD Assignment work
 
 Create a Jenkins pipeline to deploy application present at:
 
 ```bash
 https://github.com/knoldus/node-hello
```
### Requirements

1. Jenkins should be set up on a Cloud Virtual Machine and not from the local system
2. Any commits to the ‘main’ branch should trigger the job on Jenkins and start the build process
   Use Poll SCM triggers
3. The first part of the Jenkins job should be creating the package
4. The second part of the Jenkins job will be to send the package to another VM and run it there
### For validation 

we can be performed by hitting endpoints: <VM_IP>:3000 or <VM_IP>:3001

#Devops_Foundations

This repositorary for Devops Foundations
DevOps:Foundaional Concepts,Tools and Practices

Exercises For DevOps_Foundations 

This is the start of learning DevOps 

DevOps -- Plan, Develop, Build, Test, Release, Deploy, Operate, Monitor


# Step1:

Create Repo naming DevOps_Foundation

# Step2:

Go to Repo by using local PC 

git clone <Repo_link>

cd  DevOps_Foundation

git branch add_name 

git checkout add_name 
# this goes to the branch we created  "checkout"

# Step3:
Open the Readme.md file using the command code .(this is not a dot)

# code . can edit the file in text editor via terminal 

# Step4:

git add Readme.md

git commit -m "added a breif description to Readme.md"

git push -u origin add-Readme

git pull origin main

# Switch back to main branch using checkout

git checkout main

git merge add-Readme

git push 

# to delete the branch locally 

git branch -d add-readme

# to delete the branch remotely

git push origin --delete  add-readme

================================================================

CI:Automating the integration of code changes

CD:Sreamlining Deployment processes.

# Tools for CI/CD:
 EXamples:
 .Jenkins
 .GitHub Actions
 .GitLab CI/CD
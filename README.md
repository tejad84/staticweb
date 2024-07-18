# staticweb
Deploying a Static Website on Azure using ARM Templates with Azure DevOps Pipelines

we need to follow multiple steps to achieve above mentioned task.

Step1: Created a staticweb repository in the git Hub and added the ARM templates, index.html. Once it was done pushed every thing into the Git hub repo.

Step2: Now we need configure the build and release set up. For this we need to prepare the yaml file. In Yaml file we will add the necessary stages, jobs, steps and tasks.

Step3: once Yaml file was ready, we will push the file into repo. Now we need to run the pipeline for build and release. For variables I used variable group.

Step4: Once deployment was done, then we will check in the azure portal, whether it created required resources or not, once we conformed that then we can check the staticwebsite is working properly or not by using Cdn endpoint url.

Overall, I followed above mentioned steps and achieved a task.


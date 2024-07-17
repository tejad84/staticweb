# staticweb
 Deploying a Static Website on Azure using ARM Templates with Azure DevOps Pipelines 

we need to follow multiple steps to achieve above mentioned task.

Step1: Created a staticweb repository in the git Hub and added the ARM templates, index.html and azure.yaml file through local machine. Once it was done pushed every thing into the Git hub repo.

Step2: Now we need configure the build and release set up. Coming to build pipeline we need to select the yaml file to build the pipeline.

Step3: Once build pipeline was successfully ran, then will move to the release pipeline. In release pipeline enabled continuous deployment trigger for seamless deployment. In release pipeline added multiple tasks as per the requirement.

Step4: Once deployment was done, then we will check in the azure portal, whether it created required resources or not, once we conformed that then we can check the staticwebsite is working properly or not by using Cdn endpoint. 

Overall, I followed above mentioned steps and achieved task.

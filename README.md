# Task: 
  Azure DevOps Challenge
# Prerequisites: 
Create a Microsoft account and subscribe yourself to Azure/Azure DevOps(or server 2019).

  1.	Build Azure DevOps pipeline and deploy it on the Azure using a free subscription.

  a.	Use a project you trust or you are familiar with from any Git repository you want to.
        Examples: (https://github.com/HoussemDellai/WebAppWithDatabaseDemo ). Note: You have to be familiar with the source code that you are using.
    
   b.	Present the pipeline in YML:
       

            trigger:

            pool:

            steps:

            script:

            task:
            

   c.  Use MSBuld or any other build solution like CakeBuild(or similar) to buld the code to “Release”.

  2.	Pipeline should have at least two stages. Dev > QA > PROD.
  3.	Present working solution by giving us an access to your Azure/Azure DevOps environment. (You can try using vm instances or App Servis, sql instances and so on.)
  
# Additional tasks:

  1.	Implement service monitoring either using free Cloud Service provider monitoring or Datadog, Zabbix, Nagios, etc.
  2.	Implement simple automation and manual tests in Azure.
  3.	Try to commit all the tasks in your own Git repo with the solution you’ll use.

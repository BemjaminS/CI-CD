

![CICD](https://wiiisdom.com/wp-content/uploads/2022/03/rise-ci-cd-analytics-feature-img.png)

# Status badge
| **DEV**                                                                                                                                                                                                     | **STAGE**                                                                                                                                                                                                                 | **PRODUCTION**                                                                                                                                                                                                            |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| [![Build Status](https://dev.azure.com/Ben-swisa/Bootcamp-app/_apis/build/status/Bootcamp-app?branchName=main)](https://dev.azure.com/Ben-swisa/Bootcamp-app/_build/latest?definitionId=17&branchName=main) | [![Build Status](https://dev.azure.com/Ben-swisa/Bootcamp-app/_apis/build/status/Bootcamp-app?branchName=main)](https://vsrm.dev.azure.com/Ben-swisa/_apis/public/Release/badge/227f0bf8-12b7-4009-a24e-64b4f3457d20/1/1) | [![Build Status](https://dev.azure.com/Ben-swisa/Bootcamp-app/_apis/build/status/Bootcamp-app?branchName=main)](https://vsrm.dev.azure.com/Ben-swisa/_apis/public/Release/badge/227f0bf8-12b7-4009-a24e-64b4f3457d20/1/8) |

# CI / CD - Weight Tracker Application


This project deploy two environments [**Staging** , **Production**] in CI/CD

CI - Continuous integration, publish an artifact on every commit on the source code OR pull request
Trigger the Staging Release.

CD - Continuous Delivery, use the artifact to Build the environment for **staging**
, Run test to check if The project is functioning properly. 

Deploy to production Only with Manual approval.



    

# Staging & Production
## using ansible tasks:
- Create playbook.yml:
   * Include vars
   * Update & upgrade machine
   * install nodejs
   * install npm
   * Download artifact with the source code
   * Create file .env
   * install pm2 
   
- Create variable.yml
   * example of Demo var -> [Here](https://github.com/BemjaminS/Terraform-Ansible/tree/main/Ansible)

# Result:
[![Untitled-Notebook-1-1.jpg](https://i.postimg.cc/Gtmjk94q/Untitled-Notebook-1-1.jpg)](https://postimg.cc/LYGfS9B1)







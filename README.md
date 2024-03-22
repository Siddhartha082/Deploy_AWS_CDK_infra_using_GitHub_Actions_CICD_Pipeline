
# Welcome to your CDK Python project!

This is a blank project for CDK development with Python.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

This project is set up like a standard Python project.  The initialization
process also creates a virtualenv within this project, stored under the `.venv`
directory.  To create the virtualenv it assumes that there is a `python3`
(or `python` for Windows) executable in your path with access to the `venv`
package. If for any reason the automatic creation of the virtualenv fails,
you can create the virtualenv manually.

To manually create a virtualenv on MacOS and Linux:

```
$ python3 -m venv .venv
```

After the init process completes and the virtualenv is created, you can use the following
step to activate your virtualenv.

```
$ source .venv/bin/activate
```

If you are a Windows platform, you would activate the virtualenv like this:

```
% .venv\Scripts\activate.bat
```

Once the virtualenv is activated, you can install the required dependencies.

```
$ pip install -r requirements.txt
```

At this point you can now synthesize the CloudFormation template for this code.

```
$ cdk synth
```

To add additional dependencies, for example other CDK libraries, just add
them to your `setup.py` file and rerun the `pip install -r requirements.txt`
command.

## Useful commands

 * `cdk ls`          list all stacks in the app
 * `cdk synth`       emits the synthesized CloudFormation template
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk docs`        open CDK documentation

AWS Cloud Development Kit (CDK) is a popular tool for building infrastructure as code using familiar programming languages such as TypeScript, Python, and Java. Github Actions is a CI/CD platform that allows you to automate your software development workflows. 
By using Github Actions to deploy your AWS CDK infrastructure, you can automate the deployment process, ensuring that your infrastructure is always up-to-date and consistent. using Github Actions to deploy your AWS CDK infrastructure can help you automate your deployment process, making it faster, more consistent, and less error-prone. By following the steps outlined above, you can get started with Github Actions and AWS CDK deployment!

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/980d6953-08dc-4e1f-b9bc-83711b98d3aa)

# Architecture

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/4d0157ab-57bb-4260-9e5d-4bbbeba5a810)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/ea1360b6-4857-4c17-83f1-2e0f63aa6a7f)

# Initializing CDk – cdk init app –language python

#( CDK Works on non Empty Directory)  to install cdk through npm(node.js) 

#Link - https://phoenixnap.com/kb/npm-command-not-found

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/143944bc-0a46-4db0-bebb-bf93b29d2a19)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/e46cc58c-1f42-4e04-9582-73222f4289d8)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/8750d263-9fb2-49eb-bb10-71b3a6733c11)

# Push the code to Git 

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/07a48bcb-5ab5-4f90-b4da-acdc1a2002b0)

# now Enter AWS console

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/dd06834c-0bbc-4910-81e1-c2f2366fd664)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/b8a6f34c-cb5a-4549-abb1-931d6396aa28)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/cfc55aea-783b-46bb-bf8b-18f78d948af6)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/47bef882-7b26-46e6-b694-51d62ec8931a)

# To Create an  Identity role ---- head towars IAM  service console  - Click on Identity Providers

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/e83d3755-f689-4bb5-9024-ea594f2022d6)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/b6e6286f-009a-4fc2-bbb8-3ba0d5ec0f5e)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/1619ff79-e1d8-4013-add3-841cff044952)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/8e8f3a38-60d5-4648-b269-22dd37dfd01c)

# My Thumprint Token Validation – For next 7yrs 😊

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/29f979e4-c6b4-4f00-be26-c71df66394b3)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/043fc87b-10e4-47b3-b11e-514aa27a6682)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/d8a4383b-fd54-43ef-aa32-8f7a18f3dc08)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/d7f85669-f103-4b4f-947d-bebfc005127e)

# After this now define role for this provider 

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/850390b3-c5c5-4f04-8a48-5a0697079a8a)

# Select Web Identity

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/a7003864-de0f-449f-bd3c-bc6d640bc6e0)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/93b4560c-a548-4e4f-8d21-5224f7a76510)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/14f6fecf-6ef1-449d-997e-e469a8c3febe)

# Admin Acc

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/f4edbaaa-66c0-4448-9b07-3c83c0d2745a)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/9bd3d3f6-a771-40d6-94cd-20c3c63ac2f7)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/e073a7cf-ac89-4275-94a7-7385c17b3ac4)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/076c91fc-984d-4795-9092-a793661c8c85)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/e5bbc3b0-1ac7-4d2e-81a8-ecbdbde128d5)

# in IAM Add users

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/a5b1164b-65e9-4998-ba18-a6a96ee06a7c)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/53a947ce-95ca-475b-a292-42896e660e42)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/1895bd77-5ea9-4132-ac8d-32554e0ad94a)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/862e80d3-a989-405d-ab66-06714aba4f32)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/226bcf76-6d6a-46c0-b7f7-2df27370ed5f)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/23f58e11-a1b7-4b8e-8455-368b593f4f81)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/96cffcca-c598-4c51-b9eb-205578aff038)

# For this user  we need to give Access Key + tag session permission

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/de9f3efb-44ce-401b-8949-f0eb0e8bda1e)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/00c9726e-6222-4538-bc31-4d6f598357d6)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/733710e9-2255-439e-abf7-f7c27d72ec42)

# Changes made in JSON File

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/3d604d26-ce23-4ab1-ab5a-4587b7d3d20c)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/4d506ecd-8e2e-4355-9397-3165818b784d)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/b8262eec-586e-409b-ba9b-4b18081a575b)

# now Create the Policy

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/0e960c19-1c03-430b-9c99-04b2b743124a)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/64073989-5081-48cb-b21b-1662885a2fb8)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/e179f1a0-c26f-44e9-ad68-eee866d854a5)

# now to get Access Key .. go back  to IAM user ..  click  Security Credentails & Generate Access Keys

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/fd4eddde-23af-486a-9181-571406fd499a)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/1a815a42-f0cb-4dc5-aa9d-d7fd08ccc3cb)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/c776c65b-409c-4b90-b324-4da33d353873)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/0f64fb8c-1a84-401e-87dd-e8125a313881)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/61cb7920-2e51-4b2c-878c-52118dcf2ad3)

# Go to Github repo – setting- Secrete &  Varaibles – click – actions

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/3c5485c4-9b55-4ad9-94bc-aa1c9848297f)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/ffc30e80-1115-48a3-af74-b65b9b835dcd)

# Give trust relationship permission for IAM USER

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/5ba4b8c5-b1bd-4ba3-88f2-83cd7bd3bc9b)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/ea3d8ec1-bb0f-45fe-b36c-89921ef79d29)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/3ef639f6-7c05-4199-9727-e7fbb068c8e3)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/9b08383a-3e4d-4694-912b-afa26f38c199)

# Policy updated

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/1e0ed5fe-4996-4474-83ff-a438f2b8bff0)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/e6657f30-7822-4b5c-bcf9-a4070fb3897e)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/0883dad1-3651-4bdb-b16d-b3a2cad89471)

# Create yaml file _ add your user-role id

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/754cb254-177b-4b37-bbdd-1fac8f479bef)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/9b831f3f-7b4c-4d80-bab3-d7d83c3e4d67)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/e83e5bd9-4386-49c7-b8f0-ff12f648bef5)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/a25cc092-e6cc-4dae-8594-a735e41d0bd0)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/46a65a54-61a8-4922-9f30-89df46282c15)

# Now Check whether github actions are working  in fine conditions

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/0e6b1012-d901-4442-8393-3222d7b43ae2)

# click on  Deploy – AWS CDK 

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/f449b308-0819-49ce-9bc9-77c16aaa3197)

# Run Workflow

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/59816230-d63d-4599-9bbb-756f569b1c08)


![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/5a696db4-ae37-4956-ba46-795f42d4909e)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/7b7337a1-459f-417f-976e-844f6f3bfb45)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/55b46baf-c65c-4f76-8821-73825e507b94)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/20bfb18c-5781-457e-b075-8b8af33258db)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/5c629c07-ef00-4389-b0b8-4330c1ded782)

# Go to Cloud formation  

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/6eb9a443-04bb-4119-87a4-f58c686130b6)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/1a50c0b7-cccb-4e8d-bd35-7c4d1fc2f583)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/d726670a-9bbd-4729-a7f5-6bac99f4ab4a)

# Git Commit & Push

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/e0b431b8-261d-442a-94b8-3f1c061260be)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/da70fb4a-25b6-467e-a614-781ad4d3b1b2)

# Last delete all the data  in AWS

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/2fcfcb00-561e-4a31-b642-69a386db703f)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/ae59a475-e24e-41ef-9fc2-084efcaacb98)

![image](https://github.com/Siddhartha082/Deploy_AWS_CDK_infra_using_GitHub_Actions_CICD_Pipeline/assets/110781138/2ac2a760-08aa-47ed-b340-6c344d26bf02)






















































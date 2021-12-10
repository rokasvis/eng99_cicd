# Building a CI/CD pipeline
## Continuous Integration

Continuous Integration (CI): Developers merge/commit code to master branch multiple times a day, fully automated build and test process which gives feedback within few minutes, by doing so, you avoid the integration hell that usually happens when people wait for release day to merge their changes into the release branch.


## Continuous Delivery

Continuous Delivery is an extension of continuous integration to make sure that you can release new changes to your customers quickly in a sustainable way. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button. In continuous Delivery the deployment is completed manually.

## Continuous Deployment 

Continuous Deployment goes one step further than continuous delivery, with this practice, every change that passes all stages of your production pipeline is released to your customers, there is no human intervention, and only a failed test will prevent a new change to be deployed to production.

## CICD Workflow

How CICD Practices relate to each other: To put it simply, the continuous integration is part of both continuous delivery and continuous deployment. The main difference is the deployment step, in continuous delivery the deployment is done manually and in continuous deployment it happens automatically.
What is a CI CD Pipeline: The CI/CD pipeline is all about automation: Initiating code builds, automated testing, and automated deploying to the staging or production environments. It’s complex and exciting at the same time, but incredibly fast, if the output of any stage fails, the next stage will also fail.

## Docker

Docker is the one of the best virtualization platform to containerise your app, popularity and adoption of Docker is rapidly growing due to its incredible benefits! Top companies like ING, Paypal, ADP, and Spotify keep using Docker. Continuous Integration Efficiency with Docker enables you to build a container image and use that same image across every step of the deployment process. A huge benefit of this is the ability to separate non-dependent steps and run them in parallel, running applications in containers instead of virtual machines is gaining momentum in the IT industry.

## Generating SSH key

- Open git bash
- ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
- When you're prompted to "Enter a file in which to save the key," press Enter. This accepts the default file location. 
```
> Enter a file in which to save the key (/c/Users/you/.ssh/id_algorithm):[Press enter]
```

- At the prompt, type a secure passphrase. For more information, see "Working with SSH key passphrases." 

```
> Enter passphrase (empty for no passphrase): [Type a passphrase]
> Enter same passphrase again: [Type passphrase again]
```
- Copy `keyname.pub` into github to create the key
- ls ssh folder
- updates12334
# Understanding Virtual Machine Imaging with Capture (PowerShell) #

## Hands-On Lab ##

### Introduction ###

Hands-on labs are sets of step-by-step guides that are designed to help you learn how to use key Microsoft Azure services and features.  Each Lab provides instructions to guide you through the process of developing a complete application.

In this hands-on lab you will walk through configuring a virtual machine that is customized with Web Server role enabled. You will then learn how to generalize it and save it is an image so that all new virtual machines provisioned from it will have Web Server role enabled by default.

> **Note:** You can download the latest build of the Microsoft Azure Training Kit which includes a tested version of this HOL from here: http://bit.ly/WindowsAzureTK.

### Repository Structure ###

In the **root** folder of this repository you will find the Hands-On Lab (HOL) document, **HOL.md**. Before beginning with the HOL exercises, make sure you have followed all the required steps indicated at the setup section of the HOL document.

In the **Source** folder you will find the source code of each of the exercises, as well as the assets and setup scripts. Throughout the HOL you will be instructed to open and explore the different solutions from the source folder. It is typically comprised of the following subfolders:

- **Assets:** This folder contains files that are used throughout the exercises.
- **_Exercise Name_:** Each exercise that requires a programming solution has its own code folder.
  - **Begin:** The begin solution is the initial incomplete solution that you will finish by following the steps of the corresponding exercise.
  - **End:** The end solution is the final result you will achieve at the end of an exercise.
- **Setup:** This folder contains the dependency files and the setup scripts necessary to initialize specific configurations of the lab, being its execution is required in the majority of the Hands-on Labs.

### Get Started ###

In order to run the solutions of the exercises provided by this lab you will first need configure your environment and install any necessary prerequisites such as runtimes, components, or libraries. Each lab  includes setup instructions for getting started.

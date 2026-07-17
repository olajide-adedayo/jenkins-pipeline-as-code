<h1 align="center">🚀 Jenkins Pipeline as Code with GitHub SCM Integration Using SSH Authentication</h1>

<p align="center">
Building a Secure Jenkins Pipeline from GitHub Using Pipeline as Code (Jenkinsfile)
</p>

[![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?logo=jenkins&logoColor=white)](https://www.jenkins.io/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github&logoColor=white)](https://github.com/)
[![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git&logoColor=white)](https://git-scm.com/)
[![Pipeline](https://img.shields.io/badge/Pipeline-Jenkinsfile-0A66C2)](#)
[![SSH](https://img.shields.io/badge/Authentication-SSH-2EA44F)](#)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen)](#)


📖 Project Overview

This project demonstrates the implementation of Pipeline as Code by integrating Jenkins with a GitHub repository using a Jenkinsfile stored in Source Code Management (SCM). Instead of defining the pipeline directly within the Jenkins user interface, the pipeline configuration is maintained in a version-controlled GitHub repository, promoting consistency, maintainability, and collaboration.

The project covers the complete setup and configuration process, including creating a GitHub repository, authoring a Jenkinsfile, configuring a Jenkins Pipeline job to retrieve the pipeline definition from GitHub using Pipeline Script from SCM, establishing secure SSH authentication, configuring Git Host Key Verification, and executing the pipeline successfully.

Upon execution, Jenkins securely cloned the GitHub repository, retrieved the Jenkinsfile from the main branch, executed the pipeline, and completed the build successfully. This implementation demonstrates an industry-standard Continuous Integration (CI) workflow where pipeline definitions are managed as code and integrated securely with a version control system.


🎯 Business Objective

Modern software development teams require a reliable, secure, and maintainable approach to managing Continuous Integration (CI) pipelines. Defining pipeline logic directly within the Jenkins user interface makes it more difficult to track changes, collaborate across teams, and maintain consistent pipeline configurations.

This project addresses these challenges by implementing Pipeline as Code, where the pipeline definition is stored as a Jenkinsfile in a GitHub repository and retrieved automatically by Jenkins during pipeline execution. This approach enables version control, improves collaboration, simplifies pipeline maintenance, and ensures that infrastructure and automation workflows are managed using the same software engineering best practices applied to application source code.

By integrating Jenkins with GitHub using SSH authentication, the project also demonstrates a secure and production-oriented method for accessing source code repositories while maintaining a streamlined Continuous Integration workflow.

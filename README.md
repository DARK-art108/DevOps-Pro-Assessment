# Ineuron DevOps Assessment

## Introduction

The repository contains the Ineuron DevOps assessment. The assessment contains 3 question's. **Take any one question and complete it.**


## Assesment

1. **Create a URL-Shortner service using any language of your choice. The service should be able to shorten a URL and return a shortened URL. The shortened URL should be able to redirect to the original URL.**

    **Tasks:**
    * Create a System Design Document for the App.
    * The REST API should be able to create a shortened URL.
    * The REST API should be able to redirect to the original URL.
    * Dockerize the application.
    * Provision an EKS cluster on AWS using Terraform.
    * Deploy the REST-API on EKS.
    * Create a CI/CD pipeline for the application using Github Actions.
    * The pipeline should be able to deploy the application on EKS continuously when a new commit is pushed to the main branch.

2. **Deploy the below application on EKS using Terraform.**

    **About the application:**

    >The application is a Reddit Clone. It is a application where users can post the images, links, document, videos, etc.Users can also comment on the posts.Filter the posts based on the tags. Users can also upvote and downvote the posts. Users can also follow other users and see their posts in the feed.

    * Link to the application: https://github.com/DARK-art108/Reddit-Clone

    * Deployed application: https://reddit-clone-yt.vercel.app/

    Now, you have application code and the application is deployed on Vercel. You have to deploy the application on EKS using Terraform.

    **Tasks:**

    * Write the dockerfile for the application.
    * Write the kubernetes manifest for the application.
    * Provision an EKS cluster on AWS using Terraform.
    * Deploy the application on EKS.
    * Perform Continuous deployment using Jenkins.(**Optional**)



3. **Design Amazon Web Services.**

   Consider a scenario where you are working as a Devops Engineer in a Amazon.Your team is working on a project where you need to design the initial draft of a platform known as Amazon Web Services.

   The platform is a cloud computing platform that provides a set of remote computing services to users. The services include computing power, database storage, content delivery and other functionalities to help users scale and grow their applications.

   **Requirements:**

      * Functional requirements
         * Users Should be able to choose different regions for their services. eg: US, Europe, Asia, etc.
         * User should be able to choose different services like EC2, S3, RDS, etc.
         * User should be able to choose different instance types, instance size for their services. eg: small, large, or extra large or gpu instance.
         * User should be able to choose different storage types for their services. eg: SSD, HDD, etc.

      * Non-Functional requirements
         * High availability with minimal latency.
         * The system should be scalable and efficient.

      * Additional requirements
         * The system should be able to handle 1000 requests per second.
         * The system should be able to handle 1000 concurrent users.
         * The system should be able to handle 1000 concurrent connections.

   **Tasks:**

      * Create a System Design Document for the platform.
      * Create a High Level Design Document for the platform.
      * List out the best devops tools that you will use for the platform.

   **NOTE:** Their is no coding required for this question. You have to create a System Design Document and a High Level Design Document for the platform.

## How to Submit?

* DEADLINE: 6th December 2022, Tuesday
* You will recieve a google form for sharing the github link.Please make sure that your assessment should be uploaded in the github and free of plagarism.
* You will be removed if any plagarism is founded!
* All resources taken from official docs are allowed!

## Questions: 

If you have any questions about assessment or you feel stuck, feel free to ask me at [Ritesh](mailto:ritesh@ineuron.ai). Please do not hesitate to ask questions. I am here to help you. :)

![Cover image for Building Cloud Native Applications on Google Cloud](https://imgdetail.ebookreading.net/cover/cover/20200920/EB9781492089025.jpg)

[Building Cloud Native Applications on Google Cloud](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_1.html "Building Cloud Native Applications on Google Cloud")
====================================================================================================================

Author : [Rui Costa](https://ebookreading.net/search/author/Rui+Costa)

Release Date : 2022/01/01

Book Description
-----------------


    
    Companies looking to move enterprise applications to the cloud are busy weighing several options, such as the use of containers, machine learning, and serverless computing. There’s a better way. Instead of helping you fit your use case to individual technologies, this practical guide explains how to use these technologies to fit your use case.
Author Rui Costa, a learning consultant with Google, demonstrates this approach by showing you how to run your application on Google Cloud. Each chapter is dedicated to an area of technology that you need to address when planning and deploying your application. This book starts by presenting a detailed fictional use case, followed by chapters that focus on the building blocks necessary to deploy a secure enterprise application successfully.
Build serverless applications with Google Cloud FunctionsExplore use cases for deploying a real-time messaging serviceDeploy applications to Google Kubernetes Engine (GKE)Build multiregional GKE clustersIntegrate continuous integration and continuous delivery with your applicationIncorporate Google Cloud APIs, including speech-to-text and data loss preventionEnrich data with Google Cloud DataflowSecure your application with Google Cloud Identity-Aware ProxyExplore BigQuery and visualization with Looker and BigQuery SDKs
  

Table of Contents
-----------------

1. [1. Our Use Case and Framework](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#our_use_case_and_fr)
    1. [Fictional Use Case](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#fictional_use_case)
    1. [Business Objectives](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#business_objectives)
    1. [The Framework](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#the_framework)
        1. [Storing Audio Recordings](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#storing_audio_recor)
        1. [Processing Audio Recordings](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#processing_audio_re)
        1. [Gather Data from the Audio File](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#gather_data_from_th)
        1. [Securing the Application](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#securing_the_applic)
    1. [Cloud Native Checkpoint](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#cloud_native_checkp)
        1. [Abstracted from the Cloud Infrastructure](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#abstracted_from_the)
        1. [Continuous Integration and Continuous Delivery](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#continuous_integrat)
        1. [Scalability](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#scalability)
        1. [Application Reliability](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#application_reliabi)
        1. [Globally Accessible](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#globally_accessible)
        1. [Security](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#security_idQyNzEA)
    1. [Summary](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_4.html#summary_idXVykyI)
1. [2. Getting Data into Google Cloud](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#getting_data_into_g)
    1. [
          File Storage
        ](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#file_storage)
    1. [
          Block Storage
        ](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#block_storage)
    1. [
          Object-Based Storage
        ](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#object_based_storag)
    1. [
          Options for Getting Data to Cloud Storage
        ](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#options_for_getting)
    1. [Create a Bucket in the Cloud Console](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#create_a_bucket_in_)
    1. [Upload a File in the Cloud Console](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#upload_a_file_in_th)
    1. [Download the file in the Cloud Console](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#download_the_file_i)
    1. [Using the gsutil Tool](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#using_the_gsutil_to)
    1. [Create a Bucket with gsutil](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#create_a_bucket_wit)
    1. [Upload a File with gsutil](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#upload_a_file_with_)
    1. [Download the File with gsutil](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#download_the_file_w)
    1. [Using Client Libraries](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#using_client_librar)
        1. [Follow Along with Instructions using Client Libraries](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#follow_along_with_i)
        1. [Create a Bucket](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#create_a_bucket)
        1. [Create a Bucket with Bucket Locks](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#create_a_bucket_wit)
        1. [List Buckets](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#list_buckets)
        1. [Upload a File](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#upload_a_file)
        1. [Download the File](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#download_the_file)
        1. [Signed URL with Python](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#signed_url_with_pyt)
    1. [
          Uploading Audio Files for Our Framework
        ](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#uploading_audio_fil)
    1. [Cloud Functions](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#cloud_functions)
        1. [Cloud Function Libraries](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#cloud_function_libr)
        1. [GitLab CI/CD and Cloud Functions](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#gitlab_ci_cd_and_cl)
    1. [
          Cloud Native Checkpoint
        ](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#cloud_native_checkp)
    1. [
          Closing Remarks
        ](https://ebookreading.net/view/book/Building+Cloud+Native+Applications+on+Google+Cloud-EB9781492089025_5.html#closing_remarks)

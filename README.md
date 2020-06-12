# TORNADO : Intermediate Results Orchestration based Data Curation Framework for Intelligent Video Big data Analytics in the Cloud

Big data technologies are software platforms designed for distributed computing to process, analyze, and extract the valuable insights from large datasets in a scalable and reliable way. **Cloud computing** is a model for enabling ubiquitous, convenient, and on-demand network access to a shared pool of configurable computing resources that can be rapidly provisioned and released with minimal management effort or service provider interaction. The cloud is preferably appropriate to offer the big data computation power required for the processing of these large datasets. For big data analytics, numerous cloud platforms have been developed, including IBM Big Data Analytics, Amazon web service, and many more. 

Recently, the deployment of distributed computing technologies in the cloud for video big data analytics has been the center of attraction in academics and industry. Data curation is the active management of data over its life cycle,  from creation, acquisition, and initial storage to the time when it is archived or becomes obsolete. Industrial **Cloud-Based Video Analytics System**, such as Checkvideo, Intelli-Vision, assist consumers with limited functionalities, i.e., real-time video analytics service subscription. Google released a cloud-based video intelligence APIs to generate video metadata  and provided it as a black box to the developer. It does not allow the developer/researcher to plug new video analytics algorithms or to extend its functionality. Likewise, the understanding, configuration, and operationalization of big data technologies for video analytics in the cloud are tedious and time-consuming, especially in an educational environment. The existing solutions also do not consider factors like the management of high-level and low-level features while deploying video analytics algorithms. Motivated by these limitations in existing work, we propose and implement a comprehensive intermediate results orchestration based service-oriented data curation framework for large-scale online and offline video analytics in the cloud known as **TORNADO**.

## Main Features

The main features of the **TORNADO** are: 
- **TORNADO** is a scale-out data curation framework for video big data analytics in the cloud and encompasses key components like role-based access controller, device-independent video stream acquisition and synchronization, lifelong video stream monitoring tool, and big data persistence. 

- **High-level abstraction** on top of big data technologies have been developed and optimized for video big data analytics to hide the complexity of big data stack.
    
 - The proposed TORNADO effectively resolves the data curation issues throughout the life cycle of the video analytics pipeline by developing distributed data management modules both for real-time and offline analytics.
    
- TORNADO provides **video analytics algorithms and service creation and publishing APIs** that enable developers and researchers to author and publish contextual and domain-specific video analytics algorithms and services. Which are made available to the developers while following as-a-service model 
    
- TORNADO provide a unified scale-out middleware called IR Middleware against to address issues like big dimensionality, intermediate results, and video analytics pipeline orchestration. 

- We implement the proposed framework and conduct extensive experiments to validate our claims.

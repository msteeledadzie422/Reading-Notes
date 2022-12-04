# AWS EC2

_1. What is an EC2 Instance?_

  General purpose instances provide a balance of compute, memory and networking resources, and can be used for a variety of diverse workloads. These instances are ideal for applications that use these resources in equal proportions such as web servers and cod repositories. 
  
  Comput optimized instances are ideal for compute bound applications that benefit from high performance processors. Instances belonging to this family are well suited for batch processing workloads, media transcoding, high performance web servers, high performance computing (HPC), scientific modeling, dedicated gaming servers and ad server engines, machine learning inference and compute intensive applications.

  Memory opitmized instances are designed to deliver fast performance for workloads that process large data sets in memory.
  
  Accelerated computing instances use hardware accelerators, or co-processors, to perform functions, such as floating point number calculations, graphics processing, or data pattern matching, more efficiently than is possible in sofware running on CPUs.
  
  Storage optimized instances are designed for workloads that require high, sequential read and write access to very large data sets on local storage. They are optimized to deliver tens of thousands of low-latency, random I/O operations per second (IOPS) to applications.

_2. Name 2 use cases for EC2._

  Use cases for EC2 for Memory Optimized instances include memory-intensive workloads such as SAP, SQL, and NoSQL databases; distributed web scale in-memory caches, such as Memacached and Redis; in-memory databases and real-time big data analytics, such as Hadoop and Spark clusters; and other enterprise applications. 
  
  Use cases for EC2 in Accelerated Computing are machine learning, high performance computing, computational fluid dynamics, computational finance, seismic analysis, speech recognition, autonomus vehicles, and drug discovery.


_3. Provide 1 reason to use ECS instead of Heroku._

  ECS's tooling is closer to the ground level which gives you more access and control to hoist instances.


# EC2 For Humans

_1. Where can we find EC2 on the AWS Console?_

  Under the compute section of the console.


_2. Explain the general difference between T2 Micro and XL._

  It defines the relationship between memory, ram, CPU storage, etc. that determines the "power" of that instance.


_3. Explain a “Compute Cycle” to a non-technical friend._

  It is how long it takes AWS to generate a given instance.


# Elastic Beanstalk

_1. What is Elastic Beanstalk?_

  A service that deploys, manages, and scales web apps and services for you.


_2. Describe the relationship between EC2 and Elastic Beanstalk._

  Elastic Beanstalk leverages platforms such as EC2.


_3. Name some benefits of using Elastic Beanstalk._

  You can allow it to handle all of your provisioning, load balancing, and pplication health monitoring to create an auto-scaling service. 

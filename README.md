


# AWS Administration Cookbook
This is the code repository for [AWS Administration Cookbook](https://www.packtpub.com/virtualization-and-cloud/aws-administration-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781787127630), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Amazon Web Services (AWS) is a bundled remote computing service that provides cloud computing infrastructure over the Internet with storage, bandwidth, and customized support for application programming interfaces (API). Implementing these services to efficiently administer your cloud environments is a core task.

This book will help you build and administer your cloud environment with AWS. We’ll begin with the AWS fundamentals, and you’ll build the foundation for the recipes you’ll work on throughout the book. Next, you will find out how to manage multiple accounts and set up consolidated billing. You will then learn to set up reliable and fast hosting for static websites, share data between running instances, and back up your data for compliance.

Moving on, you will find out how to use the compute service to enable consistent and fast instance provisioning, and will see how to provision storage volumes and autoscale an application server. Next, you’ll discover how to effectively use the networking and database service of AWS. You will also learn about the different management tools of AWS along with securing your AWS cloud. Finally, you will learn to estimate the costs for your cloud.

By the end of the book, you will be able to easily administer your AWS cloud.

## Instructions and Navigation
All of the code is organized into folders. For example, Chapter03.



The code will look like the following:
```
AWSTemplateFormatVersion: '2010-09-09'
Parameters:
  EC2KeyName:
    Type: String
    Description: EC2 Key Pair to launch with
Mappings:
  RegionMap:
    us-east-1:
      AMIID: ami-9be6f38c
    ap-southeast-2:
      AMIID: ami-28cff44b
```



## Related Products
* [AWS Administration - The Definitive Guide](https://www.packtpub.com/virtualization-and-cloud/aws-administration-guide?utm_source=github&utm_medium=repository&utm_campaign=9781782173755)

* [Implementing DevOps on AWS](https://www.packtpub.com/virtualization-and-cloud/implementing-devops-aws?utm_source=github&utm_medium=repository&utm_campaign=9781786460141)

* [Learning AWS Lambda [Video]](https://www.packtpub.com/virtualization-and-cloud/learning-aws-lambda-video?utm_source=github&utm_medium=repository&utm_campaign=9781787289222)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781787127630">https://packt.link/free-ebook/9781787127630 </a> </p>
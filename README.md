# Hosting-Static-Website-in-AWS-S3

Amazon Simple Storage Service (Amazon S3) serves as an object storage, offering availability of data, high scalability, performance and security to industry and wide range of customers based on their requirements. It offers different storage classes. In static website, codes are fixed until modifications are made by developers. 

**Steps to Hosting a Static website**

Create an index.html file on your system

Create a bucket in S3 with ACLs enabled for object ownership and also allows public access for bucket settings 

Upload files and folders to the bucket 

Enable static website hosting found under bucket properties.

Browse url obtained from web hosting section or index.html.  Access denied?

Highlight all objects within the bucket, make public using ACL obtained at action. 

Refresh browser. 

![image](https://github.com/Edosaig/Hosting-Static-Website-in-AWS-S3/assets/107155943/8c30ff63-447d-4458-8aca-e393a7f9128f)
![image](https://github.com/Edosaig/Hosting-Static-Website-in-AWS-S3/assets/107155943/d84d3d69-483f-4ec6-8042-18a12c4e76fa)



**# If access is still denied, edit bucket policy with either codes. 

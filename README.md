# Automate-static-website-deployment-from-Github-to-S3-using-AWS-CodePipeline<br>
This blog describes the steps required to add a continuous integration and continuous delivery (CI/CD) pipeline to an existing bucket in Amazon Simple Storage Service (Amazon S3) on the Amazon Web Services (AWS) Cloud.<br>
This blog uses GitHub as a source provider. The pipeline is initiated when new items are committed, and the changes are then reflected in the S3 bucket.  The Blog will cover the creation of an AWS Account to Automatically deploy the static website from Github to S3 using AWS CodePipeline.<br><br>
Explanation about Tools AWS CodePipeline – A continuous delivery service you can use to model, visualize, and automate the steps required to release your software. You can quickly model and configure the different stages of a software release process. CodePipeline automates the steps required to release your software changes continuously.<br><br>
Amazon S3 – A highly scalable object storage service. It can be used for a wide range of storage solutions, including websites, mobile applications, backups, and data lakes.<br><br>  
Prerequisites<br>
An active AWS account Knowledge of Amazon S3<br>
and AWS CodePipeline A static website<br>
A GitHub repository.

![9ik2arowayh87k53xub9](https://user-images.githubusercontent.com/82276019/183611176-ae5877b8-6850-4f79-8fd0-3994e713b1e7.png)

.               .                     .                          .                     .                              .                     .                       .
.              .                  .                    .                     .                        .               .                      .                .

![0001](https://user-images.githubusercontent.com/82276019/211183389-18912c9c-4f8e-4cd6-9616-33b82d617898.jpg)
![0002](https://user-images.githubusercontent.com/82276019/211183390-a11d10f3-6b01-4a87-990e-ed5c8565c468.jpg)
![0003](https://user-images.githubusercontent.com/82276019/211183393-da7d9ea8-c059-43c4-97a0-d0d73f634378.jpg)
![0004](https://user-images.githubusercontent.com/82276019/211183394-ba661368-bc49-40cd-b4f9-8cdd73682dc6.jpg)
![0005](https://user-images.githubusercontent.com/82276019/211183500-bbfa65eb-66ff-4b26-b426-9dd7b26a2931.jpg)
![0006](https://user-images.githubusercontent.com/82276019/211183506-11eb4fb5-436e-46cd-ba73-483ba7510c0b.jpg)
![0007](https://user-images.githubusercontent.com/82276019/211183508-41d8d0cb-5ec1-4842-b974-eb5720d4567a.jpg)
![0008](https://user-images.githubusercontent.com/82276019/211183522-88ef97e1-33ea-4b4e-b7b3-6f1b70daf2fa.jpg)
![0009](https://user-images.githubusercontent.com/82276019/211183524-bb2469d2-841c-4e9e-a5ee-477256fa9dea.jpg)
![0010](https://user-images.githubusercontent.com/82276019/211183526-b74d1d42-1511-4676-845b-fd0d04bd9959.jpg)
![0011](https://user-images.githubusercontent.com/82276019/211183517-0abaed40-b9cf-49d4-89d4-732932dee18f.jpg)
![0012](https://user-images.githubusercontent.com/82276019/211183518-3fb191b7-5134-43bb-8def-1cf25c6b4fb8.jpg)
![0013](https://user-images.githubusercontent.com/82276019/211183519-e6d36cea-4f85-4a8e-b34a-6eccb62b40a2.jpg)
![0014](https://user-images.githubusercontent.com/82276019/211183521-d07e53c9-273b-4bcc-bc14-1ab431bee522.jpg)
![0015](https://user-images.githubusercontent.com/82276019/211183512-375dab6b-8e2e-461b-9479-a8733144a791.jpg)
![0016](https://user-images.githubusercontent.com/82276019/211183513-72086989-d1c3-407f-8f3c-ffdd8768bfb3.jpg)
![0017](https://user-images.githubusercontent.com/82276019/211183515-3905cab9-20cd-4d10-b425-7fd6742afc2a.jpg)
![0018](https://user-images.githubusercontent.com/82276019/211183509-afee9b5e-db6f-4223-80f6-1cd79cb3c77c.jpg)
![0019](https://user-images.githubusercontent.com/82276019/211183510-35e15577-ce6a-4a33-bf4c-bea40c63b769.jpg)




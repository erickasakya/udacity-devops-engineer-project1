# Udacity DevOps Engineer Project one 

## Deploy a static Website to AWS S3 Bucket and Using CLoudFront
The website is accessible on the link d20i5jjv8expys.cloudfront.net

### S3 Bucket Configurations.
#### The bucket was given a unique global name my-709730181627-bucket as seen below.
![S3 bucket was given a unique name my-709730181627-bucket](./Screenshot 2022-12-13 at 06.32.27.png)

#### The bucket has also been configured to have public acce and also turned on the static website hositing.
![image for public access](./Screenshot 2022-12-13 at 06.33.53.png)
![images showing static website hosting enabled](./Screenshot 2022-12-13 at 06.33.00.png)

#### The bucket policy was update with the provide policy document in json
![Imeage showing the policy](./Screenshot 2022-12-13 at 06.33.18.png)

#### After configuring the s3 bucket. I did upload the website files as seen below.
![website files](./Screenshot 2022-12-13 at 06.32.40.png)

### CloudFront Configuration.
#### I created the distribution under cloudFront and below are the configuration details.

#### The static website hosting on S3 bucket returned an endpoint which i copied and used as the origin domain while creating the distribution as seen below.
![distribution config](./Screenshot 2022-12-13 at 06.37.12.png)

#### I did enforce http to redirect to https hence the website having an ssl certificate. The configuration is as below.
![Enforce http to https](./Screenshot 2022-12-13 at 06.37.32.png)

#### On successfully creating the distribution was deployed wiith a domain name link for accessing the website as seen below.
![distribution details](./Screenshot 2022-12-13 at 06.36.00.png)

#### On clicking the link d20i5jjv8expys.cloudfront.net the website is loaded as below.
![Website image](./Screenshot 2022-12-13 at 07.18.32.png)
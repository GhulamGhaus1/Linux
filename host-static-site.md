
# Host static website on S3



## steps

- Create an S3 bucket
- allow all public access to bucket
- upload files
- enable static website hosting in properties 
- ```
  important step enable bucket policy.
  ````





## Allow all public access

![App Screenshot]![2022-11-22_18-50](https://user-images.githubusercontent.com/55359967/203331301-fc35f881-b4f9-4722-90ab-4299f321f208.png)


## enable static website hosting

![App Screenshot]![2022-11-22_18-51](https://user-images.githubusercontent.com/55359967/203331415-65c01395-9d82-4709-8364-0138da0068d8.png)


when you enable static website hosting you will see your bucket url there too use that to access your website.




## Bucket policy

Files wont be accessible until bucket policy is defined , I used the policy below.


```bash
  {
    "Version": "2012-10-17",
    "Id": "Policy1669070507753",
    "Statement": [
        {
            "Sid": "Stmt1669070504738",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::ghulamawsbuck/*"
        }
    ]
}
```
#### note: dont forget to add /* at the end of bucket or prefix of file names you want to access on site else bucket policy wont be aplied on objects inside the bucket

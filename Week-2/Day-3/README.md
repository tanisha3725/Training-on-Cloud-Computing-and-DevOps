# 📘 DAY 3

## AWS Key Pairs, IAM and Amazon S3

Today, we explored AWS security and access management, key pairs used for instance authentication, and Amazon S3 for object storage.

## EC2 Key Pairs

An EC2 key pair is used to authenticate access to supported EC2 instances.

We learned about RSA key pairs and the PEM file format.

- **Public key:** Installed or registered with the resource that verifies the authentication request.
- **Private key:** Kept securely by the user and used during authentication.

The private key must be protected because anyone who obtains it may be able to access resources if the corresponding authentication permissions allow it.

We also explored downloading a private key file in PEM format during key-pair creation.

## AWS IAM

IAM stands for **Identity and Access Management**. It helps control who can access AWS resources and which actions they are allowed to perform.

Important IAM components include:

- **Users:** Identities representing people or applications that need access.
- **Groups:** Collections of IAM users to which permissions can be assigned.
- **Policies:** Documents defining allowed or denied actions.
- **Roles:** Identities that provide temporary permissions to trusted users or services.

IAM is a global AWS service, meaning it is not managed as a separate independent service in each Region.

We explored creating an IAM user, creating user groups, and understanding how permissions are assigned.

## Amazon S3

S3 stands for **Amazon Simple Storage Service**. It is an object storage service used to store and retrieve data.

Important concepts include:

- **Bucket:** A container used to organize and store objects.
- **Object:** A file and its associated metadata stored in a bucket.
- **Region:** The AWS Region selected when creating a bucket.

We also discussed that S3 buckets are created in a selected AWS Region and that access to buckets and objects is controlled through permissions and configuration.

## Key Learnings

- Understood public and private keys and the PEM format.
- Learned the purpose of IAM users, groups, policies, and roles.
- Understood why IAM permissions are important.
- Learned the difference between S3 buckets and objects.
- Explored the regional nature of S3 bucket creation.

## Conclusion

Day 3 helped me understand the importance of authentication, access management, and cloud storage when working with AWS services.

# 📘 DAY 4

## AWS IAM — Identity and Access Management

Today, we learned about AWS Identity and Access Management (IAM), which helps control who can access AWS resources and which actions they can perform.

## Important IAM Concepts

- **IAM User:** An identity that can be assigned permissions to access AWS resources.
- **IAM Group:** A collection of IAM users that can share permissions.
- **IAM Policy:** A document that defines allowed or denied actions on specified resources.
- **Permissions:** Rules determining which actions an identity can perform.

IAM is a global AWS service, meaning its configuration is not restricted to one individual AWS Region.

## Practical Work

We explored IAM and practised creating an IAM user and a user group. We also learned how permissions can be assigned to control access to AWS resources.

A typical workflow includes:

1. Open the IAM service in the AWS Console.
2. Create an IAM user.
3. Create a user group when appropriate.
4. Attach a suitable permissions policy.
5. Review the user's assigned access.

## Introduction to RSA Key Pairs

We also learned about RSA key pairs and the `.pem` private-key file format used in certain cloud access workflows.

An RSA key pair contains a public key and a private key. In supported EC2 connection workflows, the public key is configured for access while the private key must be protected.

A `.pem` file may contain a private key, so it should never be uploaded to a public repository or shared with unauthorized people.

## Key Learnings

- Understood the purpose of AWS IAM.
- Learned the difference between users, groups, and policies.
- Explored the creation of users and groups.
- Learned the importance of permissions and protecting private keys.

## Conclusion

This session highlighted how IAM helps manage AWS access and why secure identity and permission management is essential in cloud environments.

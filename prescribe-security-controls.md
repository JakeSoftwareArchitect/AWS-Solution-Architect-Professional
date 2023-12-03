# Prescribe Security Controls

## IAM

Identity Access Management - used to control who can access you system and what they can access (Authentication and Authorisation). Authorisation is managed by Roles and polices.

### Identity Access Centre

> AWS IAM Identity Center makes it easy to centrally manage access to multiple AWS accounts and business applications. It provides your workforce with single sign-on access to all assigned accounts and applications from one place. 

### Single Sign-On (SSO)

Allows an external sign-on provider to authenticate users into AWS deployed apps and services. Types of SSO

- SAML
- OAuth
- OIDC
- Keberos

## Route Tables, Security Groups and Network ACLs

(See for initial mention of Security Groups and Network ACSs [design-solutions-for-organizational-complexity](design-solutions-for-organizational-complexity.md)

### Route Tables

> Each subnet in your VPC must be associated with a route table. A subnet can be explicitly associated with custom route table, or implicitly or explicitly associated with the main route table.

![Route Table Concepts](images/RouteTableConcepts.png)

![Route Table Example](images/RouteTableExample.png)

[AWS Docs][1]

## Encryption keys and certificate management

### AWS Key Management Service [KMS]

> AWS Key Management Service (AWS KMS) is a managed service that makes it easy for you to create and control the cryptographic keys that are used to protect your data. AWS KMS uses hardware security modules (HSM) to protect and validate your AWS KMS keys under the FIPS 140-2 Cryptographic Module Validation Program. China (Beijing) and China (Ningxia) Regions do not support the FIPS 140-2 Cryptographic Module Validation Program. AWS KMS uses OSCCA certified HSMs to protect KMS keys in China Regions.

[AWS Docs][2]

### Certificate Manager [ACM]

> Use AWS Certificate Manager (ACM) to provision, manage, and deploy public and private SSL/TLS certificates for use with AWS services and your internal connected resources. ACM removes the time-consuming manual process of purchasing, uploading, and renewing SSL/TLS certificates.

[AWS Docs][3]



[1]: <https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html> "Route Tables"
[2]: <https://docs.aws.amazon.com/kms/latest/developerguide/overview.html? "Key Management Service"
[3]: <https://aws.amazon.com/certificate-manager/> "Certificate Manger"

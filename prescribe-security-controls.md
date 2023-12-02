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

[1]: <https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html> "Route Tables"


# AWS Architecture Connectivity Stratergies

## AWS Direct Connect

**AWS Direct Connect**: Allow you to connect you on-prem services to AWS directly (not via internet). This can be achieved by using one of the pre-approved data centers. It's the fastet way to connect you serveces to thoses in the AWS cloud. Allows connection to different Avalability Zones, without going via the web.

**MAC Security**: 

> MAC Security (MACsec) is an IEEE standard that provides data confidentiality, data integrity, and data origin authenticity. You can use AWS Direct Connect connections that support MACsec to encrypt your data from your corporate data center to the AWS Direct Connect location. All data flowing across the AWS global network that interconnects with datacenters and Regions is automatically encrypted at the physical layer before it leaves the data center.

[AWS][1] 



## AWS VPN

**AWS VPN**: Connect your on prem services to the AWS cloud using and encryted link (Virtual Private Network)


[1]: <https://docs.aws.amazon.com/directconnect/latest/UserGuide/MACsec.html> "source"

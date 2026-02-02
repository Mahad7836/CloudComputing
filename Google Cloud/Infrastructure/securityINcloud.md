# Security in Cloud

Google Cloud security is built on multiple layers and a shared responsibility model between Google and the customer.

# Cloud Security Layers

## Operational Security
- Intrusion detection
- Reducing insider risk
- Employee verification
- Second factor authentication
- Secure Development (SD) practices

## Internet Communication Layer
- GFE and DoS protection
- Multi-tier, multi-layer DoS protection

## Storage Services
- Encryption at rest

## Service Deployment
- Encryption in communication
- RPC calls
- Hardware cryptographic layers
- User identity authentication and authorization

## Hardware Infrastructure
- Custom designed by Google
- Secure boot stack
- Cryptographic signatures
- Premises security
- Physical security
- Only a small number of people have access

# Security Responsibilities

- Shared security model between customer and Google Cloud
- Google takes care of the lower layers
- Google provides tools for customers to secure higher layers
- Data access is usually the customer’s responsibility

# Cloud Encryption

## Encryption Options
- CMEK (Customer-Managed Encryption Keys)
- CSEK (Customer-Supplied Encryption Keys)
- Client-side encryption

- TLS is used to protect data in transit
- Add some info about the options

## Client-Side Encryption
- Client-side encryption is done before sending data to Google Cloud

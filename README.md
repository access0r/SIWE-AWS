# SIWE-AWS
Authenticate Amazon Web Services with Ethereum Name Service

This code retrieves the ENS domain name associated with the Ethereum address, constructs the authentication URL, retrieves the authentication challenge, signs the challenge with the Ethereum private key, and uses the signed challenge to authenticate with AWS using Security Assertion Markup Language (SAML). Note that this code assumes that you have an AWS role set up

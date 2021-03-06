# Manage AWS SSO Certificates<a name="managecerts"></a>

AWS SSO uses certificates to set up a SAML trust relationship between AWS SSO and your cloud application's service provider\. When you add an application in AWS SSO, an AWS SSO certificate is automatically created for use with that application during the setup process\. By default, this auto\-generated AWS SSO certificate is valid for a period of five years\.

As an AWS SSO administrator, you'll occasionally need to replace older certificates with newer ones for a given application\. For example, you might need to replace a certificate when the expiration date on the certificate approaches\. The process of replacing an older certificate with a newer one is referred to as *certificate rotation*\.

**Topics**
+ [Considerations Before Rotating a Certificate](rotatecertconsiderations.md)
+ [Rotate an AWS SSO Certificate](rotatecert.md)
+ [Certificate Expiration Status Indicators](certexpirationindicators.md)
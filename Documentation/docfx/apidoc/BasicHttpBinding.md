---
uid: CoreWCF.BasicHttpBinding
summary: "Represents a binding that a Windows Communication Foundation (WCF) service can use to configure and expose endpoints that are able to communicate with ASMX-based Web services and clients and other services that conform to the WS-I Basic Profile 1.1."
remarks: *content
---

## Remarks  
The <xref:CoreWCF.BasicHttpBinding> uses HTTP as the transport for sending SOAP 1.1 messages. A service can use this binding to expose endpoints that conform to WS-I BP 1.1, such as those that ASMX clients access. Similarly, a client can use the <xref:CoreWCF.BasicHttpBinding> to communicate with services exposing endpoints that conform to WS-I BP 1.1, such as ASMX Web services or Windows Communication Foundation (WCF) services configured with the <xref:CoreWCF.BasicHttpBinding>.  
Security is turned off by default, but can be added setting the <xref:CoreWCF.BasicHttpSecurityMode> to a value other than <xref:CoreWCF.BasicHttpSecurityMode.None> in the <xref:CoreWCF.BasicHttpBinding.%23ctor%28CoreWCF.BasicHttpSecurityMode%29> constructor. It uses a "Text" message encoding and UTF-8 text encoding by default.  
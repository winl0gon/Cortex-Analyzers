### What is Binalyze AIR?

AIR is an "Automated Incident Response" platform that provides the complete feature set for:

- Remotely collecting 300+ evidence types in minutes,
- Capturing the "Forensic State" of an endpoint as a well-organized HTML/JSON report,
- Performing triage on thousands of endpoints using YARA,
- Integrating with SIEM/SOAR/EDR products for automating the response phase IR,
- Enriching alerts for eliminating false positives,
- Investigating pre-cursors generated by other security products.

#### What does this integration do?

This responder lets you start acquisition and isolation of an endpoint with Binalyze AIR. 

##### Acquisition
One of the core features of AIR is collecting evidence remotely. This feature is made possible by "Acquisition Profiles," a group of different evidence categories. With this integration, you can use following profiles:

- Full,
- Quick,
- Memory (RAM + PageFile),
- Event Logs,
- Browsing History,
- Compromise Assessment
- And much more!

##### Isolation

Endpoint isolation works by terminating all connections of an endpoint and not allowing any new connections.
When an endpoint is isolated, you can still perform tasks such as Acquisition.

For more information, please refer to [Knowledge Base](https://kb.binalyze.com/)
The program uses [Binalyze AIR API](https://www.binalyze.com)

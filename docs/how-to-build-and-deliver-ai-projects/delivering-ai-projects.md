### How to Deliver AI Projects

#### Things to Keep in Mind

-   Going from (local) POC to production is hard!
        
-   Hallucinations become hard to monitor/fix at scale
    
-   Software requires constant monitoring and maintenance. Many companies don't have the right mindset for these ongoing costs and improvements.
  

#### Cloud Platform

-  Microsoft Azure,  AWS, Google Cloud, or other providers based on your project's requirements.
    
 #### Deployment and Maintenance

-   **Containerization:**  Docker for consistent and scalable application deployment.
    
-   **Environments:** Add production and test environments for releases to facilitate testing and deployment processes.
    
-   **Continuous Integration/Continuous Deployment (CI/CD):** GitHub automations to streamline the deployment process. GitLab Pipelines is another good option.
    
-   **Testing:** Implement unit tests to ensure the reliability and functionality of your application.
    
-   **Cost Transparency:** Be clear about server/API costs and maintenance fees. Use cloud provider calculators to provide accurate estimates.
    
-   **Monitoring:**  [Sentry](https://sentry.io/for/fastapi/) or [Datadog](https://www.datadoghq.com/)
#### Security Measures

-   **API Keys and Client Credentials:** Securely manage API keys and credentials.
    
-   **Multi-Factor Authentication:** Always ensure multi-factor authentication (MFA) is in place for databases, APIs, webhooks, and other critical services.
    
-   **Sensitive Data:** For sensitive data, enhance security through the use of VPNs and encrypted connections.
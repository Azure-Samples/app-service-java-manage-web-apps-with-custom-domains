---
page_type: sample
languages: java
products: azure
services: Appservice
platforms: java
author: yaohaizh
---

## Getting Started with Appservice - Manage Web App With Domain Ssl - in Java ##


  Azure App Service sample for managing web apps.
   - app service plan, web app
     - Create 2 web apps under the same new app service plan
   - domain
     - Create a domain
   - certificate
     - Upload a self-signed wildcard certificate
     - update both web apps to use the domain and the created wildcard SSL certificate
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-java-manage-web-apps-with-custom-domains.git

    cd app-service-java-manage-web-apps-with-custom-domains

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
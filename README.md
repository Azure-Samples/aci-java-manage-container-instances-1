---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Containerinstance
  platforms: java
---

# Getting Started with Containerinstance - Manage Container Instance With Azure File Share Mount - in Java #


  Azure Container Instance sample for managing container instances with Azure File Share mount.
     - Create an Azure container instance using Docker image "seanmckenna/aci-hellofiles" with a mount to a new file share
     - Test that the container app can be reached via "curl" like HTTP GET calls
     - Retrieve container log content
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/aci-java-manage-container-instances-1.git

    cd aci-java-manage-container-instances-1

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
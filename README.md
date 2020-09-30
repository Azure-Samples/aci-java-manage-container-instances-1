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

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/aci-java-manage-container-instances-1.git

    cd aci-java-manage-container-instances-1

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
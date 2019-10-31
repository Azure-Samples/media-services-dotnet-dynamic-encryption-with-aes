---
page_type: sample
languages:
- csharp
products:
- azure
description: "The sample shows how to use Azure Media Services to dynamically encrypt your content with AES 128-bit clear encryption keys."
urlFragment: media-services-dotnet-dynamic-encryption-with-aes
---

# Dynamically encrypt assets with AES-128 using Azure Media Services v2

The sample shows how to use Azure Media Services to dynamically encrypt your content with AES 128-bit clear encryption keys. 

## How To Run This Sample

To run this sample you will need:

- Visual Studio 
- An Azure subscription

### Step 1:  Clone or download this repository

### Step 2: Update the app.config file

Update the appSettings section of the app.config file with appropriate values. For more information, see [this](https://docs.microsoft.com/azure/media-services/media-services-use-aad-auth-to-access-ams-api) topic.

```xml
	<appSettings>
		<add key="AMSAADTenantDomain" value="tenant"/>
		<add key="AMSRESTAPIEndpoint" value="endpoint"/>
		<add key="AMSClientId" value="id"/>
		<add key="AMSClientSecret" value="secret"/>

		<add key="Issuer" value="http://testacs.com" />
		<add key="Audience" value="urn:test" />
	</appSettings>
```

### Step 3: Start a streaming endpoint

Make sure to start the streaming endpoint. For more information, see: [streaming endpoints](https://docs.microsoft.com/azure/media-services/media-services-portal-manage-streaming-endpoints).

### Step 4:  Run the sample

Clean the solution, rebuild the solution, and run it. 

## About the code

For detailed information about the sample, see [Using AES-128 Dynamic Encryption and Key Delivery Service](https://azure.microsoft.com/documentation/articles/media-services-protect-with-aes128/).

## More information

You can view AMS learning paths here:

- [AMS Live Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-live/)
- [AMS on Demand Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-on-demand/)

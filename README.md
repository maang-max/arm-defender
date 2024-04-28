# arm-defender
  To enable Microsoft Defender for Cloud on a subscription, you can send a POST request to the Microsoft Azure Resource Manager (ARM) API

    Replace {access_token} with a valid access token for authentication. The token should have the necessary permissions to manage resources within the Azure subscription.
    Replace {subscriptionId} with the ID of the target Azure subscription where you want to enable Microsoft Defender for Cloud.
    Replace {resourceGroupName} with the name of the resource group containing the target subscription.
    Replace {workspaceResourceId} with the resource ID of the Log Analytics workspace where you want to store the Microsoft Defender for Cloud data. This workspace should already exist within the subscription.
    Replace {workspaceName} with the name of the Log Analytics workspace.
    Replace {orderName} with a unique identifier for the order. It can be any string value.

After replacing the placeholders, you can execute the cURL command to send the POST request and enable Microsoft Defender for Cloud on the specified subscription.

Note: The API endpoint and version specified in the request may vary based on the current Azure API version. It's recommended to refer to the official Microsoft documentation for the most up-to-date API endpoints and versions.

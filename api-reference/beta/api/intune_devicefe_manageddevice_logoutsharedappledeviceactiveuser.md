﻿# logoutSharedAppleDeviceActiveUser action

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Not yet documented
## Prerequisites
One of the following **scopes** is required to execute this API:

*DeviceManagementManagedDevices.PriviligedOperation.All*
## HTTP Request
<!-- {
  "blockType": "ignored"
}
-->
```http
POST /managedDevices/{managedDevicesId}/logoutSharedAppleDeviceActiveUser
POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/runStates/{deviceManagementScriptStateId}/managedDevice//logoutSharedAppleDeviceActiveUser
POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/runStates/{deviceManagementScriptStateId}/user//managedDevices/{managedDeviceId}/logoutSharedAppleDeviceActiveUser
POST /deviceManagement/deviceManagementScripts/{deviceManagementScriptId}/runStates/{deviceManagementScriptStateId}/managedDevice//detectedApps/{detectedAppId}/managedDevices/{managedDeviceId}/logoutSharedAppleDeviceActiveUser
```

## Request headers
|Header|Value|
|---|---|
|Authorization|Bearer &lt;token&gt; Required.|
|Accept|application/json|

## Request body
Do not supply a request body for this method.

## Response
If successful, this action returns a `204 No Content` response code.

## Example
### Request
Here is an example of the request.
```http
POST https://graph.microsoft.com/beta/managedDevices/{managedDevicesId}/logoutSharedAppleDeviceActiveUser
```

### Response
Here is an example of the response. Note: The response object shown here may be truncated for brevity. All of the properties will be returned from an actual call.
```http
HTTP/1.1 204 No Content
```




---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

// THE CLI IS IN PREVIEW. NON-PRODUCTION USE ONLY
mgc-beta identity-governance entitlement-management access-package-assignment-requests resume post --access-package-assignment-request-id {accessPackageAssignmentRequest-id} --body '{\
  "source": "Contoso.SodCheckProcess",\
  "type": "microsoft.graph.accessPackageCustomExtensionStage.assignmentRequestCreated",\
  "data": {\
    "@odata.type": "microsoft.graph.accessPackageAssignmentRequestCallbackData",\
    "stage": "AssignmentRequestCreated",\
    "customExtensionStageInstanceId": "857d0c50-466b-4840-bb5b-c92cea7141ff",\
    "state": "denied",\
    "customExtensionStageInstanceDetail": "Potential risk user based on the SOD check"\
  }\
}\
'

```
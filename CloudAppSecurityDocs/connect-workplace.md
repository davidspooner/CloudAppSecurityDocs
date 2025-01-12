---
title: Connect Workplace
description: This article provides instructions for connecting Microsoft Defender for Cloud Apps to your existing Workplace account using the App Connector APIs.
ms.date: 04/03/2023
ms.topic: how-to
---

# Connect Workplace to Microsoft Defender for Cloud Apps (Preview)

[!INCLUDE [Banner for top of topics](includes/banner.md)]

This article provides instructions for connecting Microsoft Defender for Cloud Apps to your existing Workplace account using the App Connector APIs. This connection gives you visibility into and control over your organization's Workplace use.

   > [!NOTE]
   > The Workplace API connector is rolling out gradually. If you don't see the connector yet in your environment and want to onboard soon, please fill the [Workplace API connector intake form](https://forms.microsoft.com/r/euj3pEmiM4).

## Prerequisites

- You must be signed-in as a system admin to Workplace by Meta.

   > [!NOTE]
   > A Workplace account can be connected to a single instance of Defender for Cloud Apps. Please make sure that your Workplace account is not connected to any other Defender for Cloud Apps instance.

## How to connect Workplace to Defender for Cloud Apps

1. In the Microsoft 365 Defender portal, select **Settings**. Then choose **Cloud Apps**. Under **Connected apps**, select **App Connectors**.
1. In the **App connectors** page, select **+Connect an app**, by **Workplace by Meta**.
1. In the pop-up, give the connector a descriptive name, and select **Next**.
   ![Give connector a name.](media/workplace-connector.png)

1. In the **External Link** page, select **Connect Workplace by Meta**:
   ![Connect to Workplace.](media/connect-workplace.png)

1. You'll be redirected to Workplace by Meta page.

   >[!NOTE]
   >Make sure you are logged into Workplace as System admin.

1. On the Workplace authorization page, make sure to choose the correct organization from the dropdown.

1. In the app consent page, make sure to choose **All groups** and then select **Add to Workplace.**
1. In the Microsoft 365 Defender portal, select **Settings**. Then choose **Cloud Apps**. Under **Connected apps**, select **App Connectors**. Make sure the status of the connected App Connector is **Connected**.

   > [!NOTE]
   >
   > - The first connection can take up to 4 hours to get all users and their activities.
   > - The activities that will show are the activities that were generated from the moment the connector is connected.
   > - After the connector's **Status** is marked as **Connected**, the connector is live and works.

## Next steps

> [!div class="nextstepaction"]
> [Control cloud apps with policies](control-cloud-apps-with-policies.md)

[!INCLUDE [Open support ticket](includes/support.md)]

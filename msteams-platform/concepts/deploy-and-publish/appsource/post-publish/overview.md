---
title: Maintain and support your published app
description: Maintain your published Microsoft Teams app. Analyze app usage, publish updates, promote your app, complete Microsoft 365 Certification.
ms.topic: conceptual
ms.localizationpriority: high
author: heath-hamilton
ms.author: surbhigupta
ms.date: 10/19/2022
---
# Maintain your published Microsoft Teams app

With your app listed on the Microsoft Teams store, start thinking about how you'll maintain the app going forward and increase downloads and usage.

## Analyze app usage

You can track your app usage in the [Teams app usage report](/office/dev/store/teams-apps-usage) in Partner Center. Metrics include Monthly, Daily, and Weekly active users, and retention and intensity charts. The metrics help you to track churn and frequency of usage.

Data for newly published apps takes about a week to appear in the report.

## Publish updates to your app

Submit changes to your app (such as new features or metadata) in Partner Center. These changes require a new review process.

Ensure that you check the following when you're publishing updates:

* Don't change your app ID.
* Increment your app's version number.
* In Partner Center, don't select **Add a new app** to do the update. Go to your app's page instead.

### App updates requiring user consent

When a user installs your app, they must give the app permission to access the services, and information the app requires to function. In most cases, users must do this once and new version of your app install automatically.
If you make any of the following changes to your app, however, your existing users must accept another permission request to install the update:

* Add or remove a bot.
* Change the bot ID.
* Modify a bot's one-way notification configuration.
* Modify a bot's support for uploading and downloading files.
* Add or remove a message extension.
* Add a personal tab.
* Add a channel and group tab.
* Add a connector.
* Modify configurations related to your Microsoft Azure Active Directory (Azure AD) app registration. For more information, see [webApplicationInfo](~/resources/schema/manifest-schema.md#webapplicationinfo).

## Promote your app on another site

When your app is listed in the Teams store, create a link that launches Teams and displays a dialog to install your app. For example, you can include this link as a download button on your product's marketing page.

Create the link using the following URL appended with your app ID: `https://teams.microsoft.com/l/app/<your-app-id>`.

## Complete Microsoft 365 Certification

[Microsoft 365 Certification](/microsoft-365-app-certification/docs/certification) offers assurances that data and privacy are adequately secured and protected when a third-party Microsoft 365 app or an add-in is installed in your Microsoft 365 ecosystem. The certification confirms that your app is compatible with Microsoft technologies, is compliant with cloud app security best practices, and is supported by Microsoft.

## Keep your app details updated

You must keep the following app details updated:

| App details | Description |
| --- | --- |
| Your app's listing must be kept updated. | Any changes to functionality, pricing, visual appearance, or any other updates must be accurately reflected in your app's listing.|
| You must regularly update your app to ensure that it remains compliant with the commercial marketplace policies.| Stay up to date with policy changes by subscribing to the changelog.|
| Your contact details must be kept up to date in your Partner Center account. |Microsoft will contact you occasionally to resolve any bugs or commercial marketplace policy violations in your app. If your contact details aren't updated, you might miss important notices or updates from Microsoft.|
| Maintain your app's functionality and user experience. | Your app's functionality and user experience must match or exceed the quality of experience at submission. You must maintain your app's performance.|

## Fix issues with your published app

Microsoft runs daily automation tests on apps listed on the Teams store. If issues with your app are identified, Microsoft contacts you with a detailed report on how to reproduce the issues and then provide recommendations to resolve them. Your app listing might be removed from the store if you can't fix the problems within a stated timeline.

## Possible enforcement actions

Microsoft runs automated and manual continuous health checks for all the published apps. It's intended to maintain the health and user experience of the Microsoft commercial marketplace and the Teams App store. In certain situations, Microsoft might contact you and remove your app from the commercial marketplace and the Teams App store, temporarily halt new user acquisition for your app, or take further action on your app as deemed appropriate.

**Microsoft might contact you for a resolution when:**

* Microsoft is unable to run the continuous health evaluation tests on your app as the test credentials or test environment you provided have expired.

* Microsoft sees or is made aware of critical security vulnerabilities in your app, which might endanger your users or the Microsoft commercial marketplace.

* Microsoft is made aware of issues with your app by your users through any of Microsoft’s support channels. The issues include, but aren't limited to, spammy behavior, broken functionality, or unexpected user experience bugs and user interface bugs.

* Microsoft might unilaterally take cognizance of issues highlighted by users for your app with rating and reviews.

* Microsoft has identified commercial marketplace policy failures in your app as part of the continuous health evaluation of your app post publish.

If Microsoft doesn't receive a suitable response from you, it reaches out to you again, and might simultaneously remove your app to protect users. If Microsoft receives a response that your issues are resolved and you've submitted an updated app for review, Microsoft will re-list your app when the app passes review.

**Microsoft might remove your app without prior notice (other than to inform you of that action) when:**

* Microsoft receives a takedown notice for your app alleging copyright or trademark infringement.
* Your app appears to be unmaintained or abandoned and unused.
* There's no response from you on Microsoft's reach outs.

## Discontinuing your published app

You must maintain your app's user experience as at the initial app review. If you don't maintain the app actively, or no longer wish to support the app, ensure that you discontinue your published app from your Partner Center account.

To discontinue your app:

* To remove your app from Microsoft AppSource, in your Microsoft Partner Center account, go the **Product Overview** page and select **Stop Selling**.

* Contact the Microsoft Teams App Health evaluation team at [apphealthevaluation@microsoft.com](mailto:apphealthevaluation@microsoft.com) or [teams-sas@microsoft.com](mailto:teams-sas@microsoft.com) to remove your app from the Microsoft Teams store.

* Contact your customers where appropriate. Delete or revoke any security or authorization tokens generated for your app.

## See also

[Monetize your app through Microsoft commercial marketplace](/office/dev/store/monetize-addins-through-microsoft-commercial-marketplace)

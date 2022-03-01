# Resources

* [Free M365 Developer Tenant](https://developer.microsoft.com/en-us/microsoft-365/dev-program)
* [Targeted Release](https://docs.microsoft.com/en-us/microsoft-365/admin/manage/release-options-in-office-365) - set your developer tenant to get the latest features
* [Microsoft 365 Developer Channel](https://www.youtube.com/c/Microsoft365Developer)
* [Microsoft 365 Community Channel](https://www.youtube.com/c/Microsoft365PnPCommunity)
## Teams Development

### Fundamentals
* [Get Started documentation](https://docs.microsoft.com/en-us/microsoftteams/platform/get-started/get-started-overview)
* [Get started building Microsoft Teams apps (video)](https://www.youtube.com/watch?v=EQuB8l4sccg)

### Documentation

* [Understand Teams app features](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/capabilities-overview) - Tabs, Bots, etc.
* [Teams developer documentation](https://docs.microsoft.com/en-us/microsoftteams/platform/)
* [Adaptive Cards](https://adaptivecards.io)
* [Task Modules](https://docs.microsoft.com/en-us/microsoftteams/platform/task-modules-and-cards/what-are-task-modules) - Modal dialogs for Teams apps that can display a web page or adaptive card
* [Microsoft 365 Groups and Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/office-365-groups) - There's an M365 Group inside every Team to provide membership, a SharePoint site for file storage, an Exchange shared mailbox and calendar, etc.
* [Upload a Teams application](https://docs.microsoft.com/en-us/microsoftteams/upload-custom-apps)
* [App Store validation guidelines](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/appsource/prepare/teams-store-validation-guidelines)
* [Teams app publishing](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/appsource/publish)

### Tools

* [Teams Developer Portal](https://dev.teams.microsoft.com)
* [Microsoft Teams Toolkit (Preview)](https://docs.microsoft.com/en-us/microsoftteams/platform/toolkit/visual-studio-code-overview) - A Teams code generator and developement tool set from Microsoft
* [yo teams](https://github.com/pnp/generator-teams) - A Teams code generator from the community, generates apps in TypeScript with React and Express
* [ngrok tunneling tool](https://www.ngrok.com/)
* [Do you need ngrok? (video)](https://www.youtube.com/watch?v=A5U-3o-mHD0)

### Samples

* [Teams app samples gallery](https://pnp.github.io/teams-dev-samples/)
* [HR Talent App sample](https://github.com/OfficeDev/msteams-sample-contoso-hr-talent-app)

## Azure AD SSO


* [Understanding SSO with Azure AD and Microsoft Teams](https://www.youtube.com/watch?v=SaBbfVgqZHc&t=325s)
* [Azure single vs. multitenant Apps](https://docs.microsoft.com/en-us/azure/active-directory/develop/single-and-multi-tenant-apps)
* [Azure AD Postman Collection](https://app.getpostman.com/run-collection/f77994d794bab767596d)
* [Authenticate users in Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/authentication/authentication)
* [Teams tab SSO](https://docs.microsoft.com/en-us/microsoftteams/platform/tabs/how-to/authentication/auth-aad-sso)
* [Teams bot SSO](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/how-to/authentication/auth-aad-sso-bots)
* [Teams messaging extension SSO](https://docs.microsoft.com/en-us/microsoftteams/platform/messaging-extensions/how-to/enable-sso-auth-me)
* [Claims in access tokens](https://docs.microsoft.com/en-us/azure/active-directory/develop/access-tokens?WT.mc_id=m365-38318-cxa#claims-in-access-tokens) - When troubleshooting, paste an access token into https://jwt.ms; this document explains the claims within
* [Multi-tenant architecture for SaaS apps with M365 and Azure AD (video)](https://www.youtube.com/watch?v=RjGVOFm39j0)
* [Single sign-on in Microsoft Teams tabs with Azure Active Directory](https://www.youtube.com/watch?v=kruUnaZgQaY)


### Tabs

* [Build Tabs for Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/tabs/what-are-tabs)
* [Build a tab configuration page](https://docs.microsoft.com/en-us/microsoftteams/platform/tabs/how-to/create-tab-pages/configuration-page) - These are required for tabs in Teams channels and Group conversations. They can also be used as settings pages for messaging extensions and connectors.

### Bots

* [Bots in Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/what-are-bots)
* [Bot Framework SDK](https://docs.microsoft.com/en-us/azure/bot-service/index-bf-sdk) - Use this to code your bot
* [Bot Framework Composer](https://docs.microsoft.com/en-us/composer/introduction) - Use this to build a bot visually
* [Power Virtual Agents](https://powervirtualagents.microsoft.com/) - Use this to build a bot visually for use within an enterprise
* [Consulting bot sample](https://github.com/pnp/teams-dev-samples/tree/main/samples/app-consulting-bot)
* [Bot Composer videos](https://aka.ms/teams-bot-composer-videos)

### Sending notifications

* [Webhooks and connectors](https://docs.microsoft.com/en-us/microsoftteams/platform/webhooks-and-connectors/what-are-webhooks-and-connectors) - The easy way to send notifications but only works in a Teams channel, not personal or group chats
* [Activity feed](https://docs.microsoft.com/en-us/graph/teams-send-activityfeednotifications)
* [Proactive bots](https://docs.microsoft.com/en-us/microsoftteams/platform/bots/how-to/conversations/send-proactive-messages)

### Messaging Extensions

* [Messaging extensions documentation](https://docs.microsoft.com/en-us/microsoftteams/platform/messaging-extensions/what-are-messaging-extensions)
* [Build a configuration page](https://docs.microsoft.com/en-us/microsoftteams/platform/tabs/how-to/create-tab-pages/configuration-page) - These can be used as settings pages for messaging extensions

### Meeting Apps

* [Apps for Teams meetings](https://docs.microsoft.com/en-us/microsoftteams/platform/apps-in-teams-meetings/teams-apps-in-meetings)
* [Enable and configure apps for Teams meetings](https://docs.microsoft.com/en-us/microsoftteams/platform/apps-in-teams-meetings/enable-and-configure-your-app-for-teams-meetings)
* [Azure Communication Services](https://azure.microsoft.com/en-us/services/communication-services/) - Azure services that allow apps outside of Teams to chat and have voice and video meetings
* [Microsoft Teams Meeting App – Record and playback attendee names (video)](https://www.youtube.com/watch?v=djmgcGFLnas)
* [Create interactive meeting apps for Microsoft Teams (video)](https://www.youtube.com/watch?v=jDfGpTSZ9zA)

### Teams JavaScript API

* [Teams JavaScript SDK](https://docs.microsoft.com/en-us/javascript/api/overview/msteams-client)
* [Teams JavaScript SDK v2 (Preview)](https://docs.microsoft.com/en-us/microsoftteams/platform/m365-apps/using-teams-client-sdk-preview)

### Microsoft Graph API

* [Getting Started with Microsoft Graph](https://developer.microsoft.com/en-us/graph/get-started)
* [Microsoft Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer)
* [Microsoft Graph Postman Collection](https://docs.microsoft.com/en-us/graph/use-postman)
* [OData, the way to REST](https://www.odata.org/) - Microsoft Graph uses OData conventions for access to collections of data
* [Microsoft Graph Fundamentals lab](https://docs.microsoft.com/en-us/learn/paths/m365-msgraph-fundamentals/)
* [Microsoft Graph Toolkit lab](https://docs.microsoft.com/en-us/learn/modules/msgraph-toolkit-intro/)
* [Microsoft Graph Scenarios lab](https://docs.microsoft.com/en-us/learn/paths/m365-msgraph-scenarios/)
* [Microsoft Graph SDK](https://docs.microsoft.com/en-us/graph/sdks/sdks-overview)

## Commercial Marketplace

* [What is the Microsoft commercial marketplace?](https://docs.microsoft.com/en-us/azure/marketplace/overview)
* [Commercial marketplace documentation](https://docs.microsoft.com/en-us/azure/marketplace/)
* [Microsoft partner network](https://partner.microsoft.com/en-us/solutions/the-commercial-marketplace)
* [Microsoft Teams ISV app monetization](https://devblogs.microsoft.com/microsoft365dev/microsoft-teams-isv-app-monetization-capabilities-now-available-in-developer-preview/) - Preview program announcement
* [SaaS fulfillment APIs in the Microsoft commercial marketplace](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/pc-saas-fulfillment-apis)
* [Managing the SaaS subscription life cycle](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/pc-saas-fulfillment-life-cycle)
* [App Source simulator and monetized M365 app samples](https://aka.ms/TeamsMonetization/codesamples)




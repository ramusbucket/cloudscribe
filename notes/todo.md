TODO:

Make sure all the Security Settings under Administration > Security Settings are implemented
Some of them may currently just update the settigns but no logic enforces the settings

There should be a way for an admin to approve an account and generate an email to the new user letting him know of approval

Check "Require Confirmed Phone" && provide SMS settings
** Newly registered user should not be able to login until phone is verified by sms
** User should have an opportunity to provide a phone number during registration



Backlog Plans and ideas
Support for IdentityServer4 - main goal is I should be able to mix and mingle SPA features into the same web app with MVC features, and jwt auth works in addition to cookie auth

If the Registration Agreement is populated, if the user registers with social auth this is not currently enforced, the user can register without having checked the box. Need to detect new user creation for social auth and if needed redirect to another page to require the user to agree to the terms. but to do this would require a new field on user account to indicate if he agreed

Support for security questions and answers?

Support for custom account/registration fields?

Telemetry - I would like to implement telemetry to capture activities, but I want an abstraction of my own as opposed to being strongly coupled to Application Insights
I want to be able to log activities to an activity stream - ie into a CRM - there should be interfaces for this in cloudscribe core, but implementation will be outside or can use Application Insights

Need some kind of help system to add contextual help for various settings that may need explanation


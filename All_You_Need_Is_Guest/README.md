# All You Need Is Guest

[View on BHUSA2023 agenda](https://www.blackhat.com/us-23/briefings/schedule/index.html#all-you-need-is-guest-32647)

## Abstract

Azure AD guest accounts are widely used to grant external parties limited access to enterprise resources, with the assumption that these accounts pose little security risk. As you're about to see, this assumption is dangerously wrong.

In this talk, we will show how guests can leverage undocumented APIs to bypass limitations and gain unauthorized access to sensitive business data and capabilities including corporate SQL servers, SharePoint sites, and KeyVault secrets. Furthermore, we will reveal how guests can create and control internal business applications to move laterally within the organization. All capabilities presented in the talk will be demonstrated with the default Office 365 and Azure AD configuration.

Next, we will drop PowerGuest, a powerful tool designed to uncover the true scope of guest access in your tenant. PowerGuest can automate limitation bypass, enumerate and dump all accessible data, and allow for interactive non-read actions by the researcher.

Finally, we will make up for shattering the illusion of guests having limited access by sharing concrete steps to harden your Azure AD and Office 365 configurations to prevent such attacks and suggest detection logic to catch them if a change in configuration is not possible.

### Tools and Demos

- [Power-pwn](https://github.com/mbrg/power-pwn) - An offensive and defensive security toolset for Microsoft 365 Power Platform

- [6 minute talk teaser, YouTube](https://www.youtube.com/watch?v=ZuCDzjzT8VM)
 
- [It's super easy to get a guest account, YouTube](https://www.youtube.com/watch?v=rDFZmpNz0RM)

### Articles

- [Low-Code / No-Code Security, Dark Reading](https://www.darkreading.com/author/michael-bargury)

- [USB DeadDrops](https://deaddrops.com)

- [Backdooring and Hijacking Azure AD Accounts by Abusing External Identities, BlackHat 2022](https://www.blackhat.com/us-22/briefings/schedule/#backdooring-and-hijacking-azure-ad-accounts-by-abusing-external-identities-26999)
 
- [Phishing thru Teams, PSCONFEU 2020](youtube.com/watch?v=NN1nIbp-z70)

- [Directory enumeration with guests, AADInternals](aadinternals.com/post/quest_for_guest)

- [Known ways to bypass Power Platform DLP policies](https://www.zenity.io/microsoft-power-platform-dlp-bypass-uncovered-finding-5-parent-and-child-flow-execution/)

- [Family of client IDs research](https://github.com/secureworks/family-of-client-ids-research/)

- [OWASP LCNC Top 10](https://owasp.org/www-project-top-10-low-code-no-code-security-risks/)

## Talk materials

- Slides pending

- Video pending

- [6 minute talk teaser, YouTube](https://www.youtube.com/watch?v=ZuCDzjzT8VM)

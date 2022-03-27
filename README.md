# Want More Features?
Check out our advanced drop-in replacement module here: https://marketplace.whmcs.com/product/4229-namesilo-registrar-advanced

It includes more advanced functionality like SRV record management, end-to-end client area domain transfer management, admins can configure name servers to auto-set upon transfer completion, and more.

# Maintenance Plan
Our goal is to maintain this free NameSilo module by fixing bugs and ensuring compatibility with WHMCS releases. We welcome bug reports via GitHub Issues. Feature requests may be considered where they do not conflict with or overlap with features in our advanced module.

EVERYTHING BELOW IS STOCK INFORMATION FROM UPSTREAM

Latest updates include: registry premium domain name pricing and TLD price sync (sync ALL TLD price with one click inside WHMCS)

Features in next release in September: Domain sync and Transfer sync

# whmcs
NameSilo's WHMCS 8.x Registrar Module

Installing the NameSilo module for WHMCS is easy and only takes a few minutes. This module allows WHMCS to
interface with NameSilo’s API to provide Registration, Transfer, Renewal, EPP Authcodes, DNS management and
domain updates to be processed in real-time. In addition, we have included a script to sync Expiry and Due Dates
for domains to ensure even if something changes outside of WHMCS that it will remain up-to-date.



TO INSTALL THE MODULE:

1. Upload the “namesilo” folder to your WHMCS Registrar Modules Directory with a standard FTP client.
(e.g. http://www.yourdomain.com/whmcs/modules/registrars/namesilo)

2. Log in to WHMCS, under "Setup" click on "Domain Registrars" select “NameSilo” from the list.

3. Fill in the details. *NOTE: Only your live API key is required. All other fields are optional at this time



TO UPGRADE THE MODULE:

1. Upload and overwrite the existing “namesilo” folder in your WHMCS Registrar Modules Directory with a
standard FTP client (e.g. http://www.yourdomain.com/whmcs/modules/registrars/namesilo).

2. Log in to WHMCS and under "Setup" click on "Domain Registrars" select "NameSilo" from the list.

3. Update any details that are still blank.


**To enbale premium domain pricing support select NameSilo as the default lookup provider (Setup > Products/Services > Domain Pricing > Lookup Providers).

**Premium domain orders need to be completed manually, premium pricing and customer ordering work as normal

**TLD Sync support was added, to use it go to Utilities > Registrar TLD Sync (requires at least WHMCS 7.10).


SUPPORT

If you have any questions, suggestions, or bug issues please feel free to email support@namesilo.com.

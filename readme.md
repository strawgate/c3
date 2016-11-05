# Inspiration

C3 exists to provide a large collection of content that is general enough to be applicable everywhere but specific enough to solve problems organizations face today without modification or advanced coding. The best part about C3 is that it is currently used in production! C3 is made up primarily of content I have created but also relies heavily on other community contributors.

# Production Sites

## [C3 Inventory](https://github.com/strawgate/C3-Inventory)

The goal of C3 Inventory is to provide expansive inventory capabilities for organizations to inventory and assess their endpoint and server environments.

The capabilities of C3 Inventory managing and analyzing the following:

* Active Directory
* Applications (installed and running)
* Dell BIOS Configuration
* Dell Driver Update Fixlets
* Drives and Volumes
* Hardware
* Microsoft Group Policy
* Microsoft Hyper-V (Guest and Host)
* Network (Wired and Wireless)
* Network Shares and Share Permissions
* Operating System
* Pagefile and Swap Space
* Pending Restart
* Printers (local and network)
* Services and Service Monitoring
* SNMP Configuration
* System Center Configuration Manager Agent
* Users and Groups
* Temporary Administrative Rights
* Trusted Platform Module
* UEFI and SecureBoot
* VMWare (Guest)
* Virtual Private Network Configurations
* Windows Repair
* Windows Management Interface

C3 Inventory also includes the following Dashboards/Wizards:

* BigFix Query
 * Provides BigFix Fast Query in the Windows Console

C3 Inventory is available to be synced directly into your environment using the BigFix.Me Sync Tool and it's content can be downloaded individually from [BigFix.Me](https://bigfix.me/site/details/10400#tabs-2) and [Github](https://github.com/strawgate/C3-Inventory).

## [C3 Patch](https://github.com/strawgate/C3-Patch)

C3 Patch is both a set of tools and a content site. The C3 Patch Content Site hosts patches for more than 80 third-party applications covering software on both macOS and Windows.

Supported content is automatically tested on various Operating System, Edition, and Architecture combinations before publishing to BigFix.Me and we do our best to support software prerequisites.

For each supported application we provided Fixlets to deploy the software, update the software, and remove the software. Software Categories included in C3 Patch include:

* Accessibility
 * Jaws
* Browsers
 * Chrome
 * Firefox
 * Opera
* Development
 * Atom
 * Eclipse
 * Scratch
 * etc.
* Plug-ins
 * Adobe Air
 * Silverlight
* Productivity
 * NotePad++
* Security
 * Microsoft EMET
 * MalwareBytes
* Systems Management
 * Dell Command | Configure
 * Dell Command | Update
* Utilities
 * Putty

And that's just a sampling! For a **full list of supported software** please visit the C3 Patch site on [GitHub](https://github.com/strawgate/C3-Patch).

If you have issues with a C3 Patch or you would like to recommend changes to the actionscript or relevance of a patch [please create on issue on the C3 Patch GitHub](https://github.com/strawgate/C3-Patch/issues).

C3 Patch is available to be synced directly into your environment using the BigFix.Me Sync Tool and it's content can be downloaded individually from [BigFix.Me](https://bigfix.me/site/details/10397).

## [C3 Protect](https://github.com/strawgate/C3-Protect)

C3 Protect is a set of content related to the various aspects of securing workstations. From Application Whitelisting to Anti-Virus management and Endpoint Encryption, C3 Protect lets organizations use IBM BigFix for things that would typically require engaging with a third-party vendor.

* Application Whitelisting
 * Applocker
* Antivirus Management
 * Avast Anti-Virus
 * McAfee ePO
 * McAfee Endpoint Security
 * Symantec Endpoint Protection
* Exploit Protection
 * Microsoft EMET
* Hard Disk Encryption
 * BitLocker
 * FileVault 2
* Network Firewall
 * macOS Application Firewall
 * Windows Firewall
* Trusted Platform Module
 * Provisioning
* Virtualization Based Security
 * Credential Guard
 * DMA Protection
 * Hypervisor Code Integrity (HVCI)

C3 Protect is available to be synced directly into your environment using the BigFix.Me Sync Tool and it's content can be downloaded individually from [BigFix.Me](https://bigfix.me/site/details/10398#tabs-2) and [Github](https://github.com/strawgate/C3-Protect).

## [C3 Platform Kickstart](https://github.com/strawgate/C3-Platform-Kickstart)

C3 Platform Kickstart focuses on providing all of the infrastructure-related content you need to properly configure you're environment.

Specifically, C3 Platform Kickstart helps with:

* Client Audit
 * Issues
 * Performance
 * Settings
* Client Configuration
 * Cache Settings
 * Command Polling
 * CPU Usage
 * Log Retention
 * Relays
* Relay configuration
 * Cache Settings

C3 Platform Kickstart is available to be synced directly into your environment using the BigFix.Me Sync Tool and it's content can be downloaded individually from [BigFix.Me](https://bigfix.me/site/details/10403#tabs-2) and [Github](https://github.com/strawgate/C3-Platform-Kickstart).


## [C3 Power Management](https://github.com/strawgate/C3-Power-Management)

C3 Power Management is all about managing and reporting on the power policies defined and in-use on managed devices.

Supported Power Management tools include:

* 1E NightWatchman
* macOS Power Management
* Windows Power Management

In addition, C3 Power Management includes analyses to pull information related to the last system wake-up and a probe to diagnose system power efficiency issues.

C3 Power Management is available to be synced directly into your environment using the BigFix.Me Sync Tool and it's content can be downloaded individually from [BigFix.Me](https://bigfix.me/site/details/10399#tabs-2) and [Github](https://github.com/strawgate/C3-Power-Management).

# Beta Sites

## [C3 Remote Control](https://github.com/strawgate/C3-Remote-Control)

C3 Remote Control provides content for reporting on remote access usage in your organization.

Supported Remote Control tools include:

* Microsoft Remote Assistance
* Microsoft Remote Desktop
* TeamViewer

C3 Remote Control is available to be synced directly into your environment using the BigFix.Me Sync Tool and it's content can be downloaded individually from [BigFix.Me](https://bigfix.me/site/details/10401#tabs-2) and [Github](https://github.com/strawgate/C3-Remote-Control).

## [C3 Software Usage](https://github.com/strawgate/C3-Software-Usage)

C3 Software Usage uses AppLocker in Audit-Only mode on Windows to provide application usage tracking including usage count and last use date for various applications.

C3 Software Usage is available to be synced directly into your environment using the BigFix.Me Sync Tool and it's content can be downloaded individually from [BigFix.Me](https://bigfix.me/site/details/10406#tabs-2) and [Github](https://github.com/strawgate/C3-Software-Usage).

# Automatic Content Syncing

## BigFix.Me Sync Tool

The best way to get C3 content into your environment is by using the BigFix.Me Sync Tool. The Sync tool will automatically sync the content into your environment keeping it up to date when new content is published.

[Instructions for setting up the sync tool are available here.](https://forum.bigfix.com/uploads/default/original/2X/9/93f211da4939ace06d14b501a3ebb22c7c53fb4f.pdf). If you have issues setting up the sync tool [please post on the BigFix Forums with your issue](http://forum.bigfix.com) or [reach out to me directly on the forum](https://forum.bigfix.com/users/strawgate).

# Manual Content Download

Organizations looking to test content without syncing it directly into their environment can always manually download and import content.

## GitHub

All content is available in the GitHub Repositories listed for each C3 site. On GitHub you can favorite or watch the repositories for changes, you can download individual fixlets and analyses for import or you can download the entire site as a zip.

## BigFix.Me

You can also download the fixlets directly from BigFix.Me. Each fixlet and analysis is available for download.

# Support

## GitHub

Primary issue tracking for each C3 Site occurs on its own GitHub project page. Anyone with a GitHub account can report an issue via this mechanism, receive updates as the issue is categorized and prioritized, and receive a notification when their issue has been fixed.

## Forum

If you have questions or concerns you can always [contact me directly on the BigFix Forums](https://forum.bigfix.com/users/strawgate).

## Email

Customers using C3 in Production have access to free email support -- simply contact me through one of the above mechanisms to receive an email address that you can contact for direct support.

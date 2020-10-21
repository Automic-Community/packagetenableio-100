## Getting Started:


###### Description

Tenable.io - Tenable.io, the world’s first Cyber Exposure platform, arms Security with the visibility to see their entire cyber attack surface at all times (from IT to Cloud to IoT to OT) and arms the CISO, C-suite and Board of Directors with the insight to focus on the issues which matter most and make better strategic decisions.
(https://www.tenable.com/products/tenable-io)

Components for Tenable Nessus:

1. Scans - you can create, view, and manage scans and resources. Users can see all the scans that have been performed.
2. Policy - you can create a policy using multiple plugins or you can use the predefined policy.
3. Plugins - You can use any combination of Nessus provided plugins to create a policy.
4. Scanner Templates - you can use Nessus defined scanner templates to quickly create a scan. The pre-defined templates reference predefined policies like Basic 5. 5. Network Scan, Crediential Patch Audit, Web Application Test, etc.
		
###### Actions

1. Get Scan Details
2. Get Scan Status
3. Create Scan
4. Get Scan Template
5. Get Agent Group
6. Update Scan
7. Launch Scan
8. Pause Scan 
9. Resume Scan
10. Stop Scan
11. Download Web App Scan Results
12. Download Scan Results
13. Check Scan Status


###### Prerequisite:

1. Automation Engine should be installed.
2. Automic Package Manager should be installed.

###### Steps to install action pack source code:

1. Clone the code to your machine.
2. Go to the package directory.
3. Run the command apm upload in the directory which contains package.yml (source/):
   Ex. **apm upload -force -u <Name>/<Department> -c <Client-id> -H <Host> -pw <Password> -S AUTOMIC -y -ia -ru**


###### Package/Action Documentation

Please refer to the link for [package documentation](source/ae/DOCUMENTATION/PCK.AUTOMIC_TENABLE_IO.PUB.DOC.xml)

###### Third party licenses:

The third-party library and license document reference.[Third party licenses](source/ae/DOCUMENTATION/PCK.AUTOMIC_TENABLE_IO.PUB.LICENSES.xml)

###### Useful References

1. [About Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_AboutPacksandPlugins.htm?Highlight=Action%20packs)
2. [Working with Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_WorkingWith.htm#link10)
3. [Actions and Action Packs](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#_Common/ReleaseHighlights/RH_Plugin_PackageManager.htm?Highlight=Action%20packs)
4. [PACKS Compatibility Mode](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#AWA/Variables/UC_CLIENT_SETTINGS/UC_CLIENT_PACKS_COMPATIBILITY_MODE.htm?Highlight=Action%20packs)
5. [Working with actions](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/AB_WorkingWith.htm#link4)
6. [Installing and Configuring the Action Builder](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/install_configure_plugins_AB.htm?Highlight=Action%20packs)

###### Distribution: 

In the distribution process, we can download the existing or updated action package from the Automation Engine by using the apm build command.
Example: **apm build -y -H AE_HOST -c 106 -u TEST/TEST -pw password -d /directory/ -o zip -v action_pack_name**
			
			
###### Copyright and License: 

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)

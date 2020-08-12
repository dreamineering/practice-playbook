---
title: Installation
description: ''
position: 1
category: Getting Started
---

Please install the Desktop Application appropriate to your country.

> [GPM UK](http://software.gensolve.com/gpmuk/install.htm)

If you are interested in the **Audiology** product please _email sales@gensolve.com_

If you are running antivirus software you need to **configure threat exclusions** before installation

See [Troubleshooting Installation Steps](http://docs.gensolve.com/help/gpm_uk/desktop/Processes/Installation___Troubleshooting/Installation.htm) for more details.

Right-click on the GPM icon in the bottom taskbar and select **Pin to taskbar**. This will enable you to quickly start GPM when starting your machine.

## System Requirements

A practice will need at least one machine with the following specs to access the full system functionality.

### Internet Connection

**Reliable** 1Mbps download minimum, 2Mbps or greater

If you get a timeout warning when logging into GPM please refer to Microsoft's [troubleshooting guide](https://support.microsoft.com/en-us/help/936211/how-to-troubleshoot-network-connectivity-problems-in-internet-explorer) to confirm you have a reliable internet connection.

### Hardware

- RAM (System Memory) - 2GB or greater
- Free space on your hard drive - 1GB or greater
- Screen resolution - 1024×768 minimum, 1280×1024 or greater

### Software

- Operating System - Windows 10
- MS Office -2007 or later

### Antivirus 

Many businesses that use GPM rely only on Windows 10's Defender security center and we ensure GPM functions correctly with each Windows 10 security update. But we do not keep up with changes to all antivirus options.

As a general principle, antivirus software needs to be configured with rules that allow Gensolve to be installed and access the internet and to preserve these rules when antivirus software updates occur.

If you have Antivirus software, but are unsure of how to configure the antivirus software to allow GPM to be installed then you will need to speak with third party security expert.


#### McAfee

Add an exception to McAfee firewall by following the below mentioned steps, you can add an exception to the McAfee Firewall:

Open the main McAfee window and then left click on the Firewall section of the upper left navigation menu.

![01-mcafee-main](https://drive.google.com/uc?id=1_LIZemK6avaNyr-PNPLXYKhgZMlnATB0)

Next, left click on the “Settings” link to the right.

![02-mcafee-settings](https://drive.google.com/uc?id=1_Y1W2-6sXiuH4d3gRrhpeQM6ZLaGsyBk)

Left click on the drop down menu arrow next to Program Permissions.

![03-mcafee-settings](https://drive.google.com/uc?id=1_YKFSPXyOsWYpaNUqP7Hd7Wjrd0fCvg1)

Now left click the “Add” button.

![04-mcafee-settings](https://drive.google.com/uc?id=1_YWCMdSgAqyzjLJ2p2FX5-br_KDhmGVM)

Make sure that “Access” is set to “Full” and then left click on the “Browse…” button.

![05-mcafee-settings](https://drive.google.com/uc?id=1_r3uFB7GDIYoxvKAJ4NaO5LgvJ6yQYKP)

Browse the list starting from “My Computer” to the “Gensolve” folder. The path of the program is

```
C:\ProgramData\Gensolve
```

Select “Gensolve.exe”

You can now left click on the “Save” button to finish adding “Gensolve.exe” as an exception

![06-mcafee-settings](https://drive.google.com/uc?id=1_rwzNvXlyYPl7P0463_PZfl1ooi1b6-f)

#### Norten

#### Avast



## Install Errors

### SAP Crystal Reports Fails to Install

SAP Crystal Reports is a dependency for Reporting in the Desktop Application. If attempts to install GPM continue to fail with a warning about SAP Crystal Reports it is likely that an earlier attempt to install SAP has failed. Possibly blocked from installing by your antivirus software.

To fix the problem:

- In the Windows Menu goto _Add or Remove Programs_
- Uninstall all references to _SAP Crystal Reports Runtime Engine for .NET Framework_
- Delete the SAP Business Objects folder _c:\program files (x86)\SAP Business Objects_
- Ensure your **antivirus software is configured** to enable GPM to install

You should now be able to install GPM.


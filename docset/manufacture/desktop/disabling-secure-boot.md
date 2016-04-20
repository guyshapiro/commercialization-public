---
author: Justinha
Description: Disabling Secure Boot
MS-HAID: 'p\_adk\_online.disabling\_secure\_boot'
MSHAttr: 'PreferredLib:/library/windows/hardware'
title: Disabling Secure Boot
---

# Disabling Secure Boot


You may need to disable Secure Boot to run some PC graphics cards, hardware, or operating systems such as Linux or previous version of Windows.

Secure Boot helps to make sure that your PC boots using only firmware that is trusted by the manufacturer.

For most PCs, you can disable Secure Boot through the PC’s firmware (BIOS) menus. For logo-certified Windows RT 8.1 and Windows RT PCs, Secure Boot is required to be configured so that it cannot be disabled.

**Warning**  
-   After disabling Secure Boot and installing other software and hardware, it may be difficult to re-activate Secure Boot without restoring your PC to the factory state.

-   Be careful when changing BIOS settings. The BIOS menu is designed for advanced users, and it's possible to change a setting that could prevent your PC from starting correctly. Be sure to follow the manufacturer's instructions exactly.

 

**To disable Secure Boot:**

1.  Before disabling Secure Boot, consider whether it is necessary. From time to time, your manufacturer may update the list of trusted hardware, drivers, and operating systems for your PC. To check for updates, go to Windows Update, or check your manufacturer's website.

2.  Open the PC BIOS menu. You can often access this menu by pressing a key during the bootup sequence, such as F1, F2, F12, or Esc.

    Or, from Windows, hold the Shift key while selecting **Restart**. Go to **Troubleshoot &gt; Advanced Options: UEFI Firmware Settings**.

3.  Find the **Secure Boot** setting, and if possible, set it to **Disabled**. This option is usually in either the **Security** tab, the **Boot** tab, or the **Authentication** tab.

4.  Save changes and exit. The PC reboots.

5.  Install the graphics card, hardware, or operating system that’s not compatible with Secure Boot.

    In some cases, you may need to change other settings in the firmware, such as enabling a Compatibility Support Module (CSM) to support legacy BIOS operating systems. To use a CSM, you may also need to reformat the hard drive using the Master Boot Record (MBR) format, and then reinstall Windows. For more info, see [Windows Setup: Installing using the MBR or GPT partition style](windows-setup-installing-using-the-mbr-or-gpt-partition-style.md).

6.  If you’re using Windows 8.1, you may see a watermark on the desktop alerting you that Secure Boot is not configured correctly. Get this [update to remove the Secure Boot desktop watermark](http://go.microsoft.com/fwlink/p/?linkid=329932).

**To re-enable Secure Boot:**

1.  Uninstall any graphics cards, hardware, or operating systems that aren’t compatible with Secure Boot.

2.  Open the PC BIOS menu. You can often access this menu by pressing a key during the bootup sequence, such as F1, F2, F12, or Esc.

    Or, from Windows: go to **Settings charm &gt; Change PC settings &gt; Update and Recovery &gt; Recovery &gt; Advanced Startup: Restart now**. When the PC reboots, go to **Troubleshoot &gt; Advanced Options: UEFI Firmware Settings**.

3.  Find the **Secure Boot** setting, and if possible, set it to **Enabled**. This option is usually in either the **Security** tab, the **Boot** tab, or the **Authentication** tab.

    On some PCs, select **Custom**, and then load the Secure Boot keys that are built into the PC.

    If the PC does not allow you to enable Secure Boot, try resetting the BIOS back to the factory settings.

4.  Save changes and exit. The PC reboots.

5.  If the PC is not able to boot after enabling Secure Boot, go back into the BIOS menus, disable Secure Boot, and try to boot the PC again.

6.  In some cases, you may need to refresh or reset your PC to its original state before you can turn on Secure Boot. For more info, see [How to restore, refresh, or reset your PC](http://go.microsoft.com/fwlink/p/?linkid=279534).

7.  If the above steps don’t work, and you still want to use the Secure Boot feature, contact your manufacturer for help.

    For additional troubleshooting steps for PC manufacturers: see [Secure Boot isn't configured correctly: Determine if the PC is in a manufacturing mode (info for manufacturers)](secure-boot-isnt-configured-correctly-determine-if-the-pc-is-in-a-manufacturing-mode--info-for-manufacturers.md).

## <span id="related_topics"></span>Related topics


[Secure Boot Overview](secure-boot-overview.md)

[Secure Boot isn't configured correctly: troubleshooting](secure-boot-isnt-configured-correctly-troubleshooting.md)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_adk_online\p_adk_online%5D:%20Disabling%20Secure%20Boot%20%20RELEASE:%20%284/11/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




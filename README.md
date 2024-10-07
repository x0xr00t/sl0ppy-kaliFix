# sl0ppy-Kalifix
A small fixer for common kali update|upgrade issues.This tool fixes most of the common issues on kali|deb.. It has a downgrade option for if needed. 

# Version 
* v0.7

# Side Note: 
this not fixes all issues, just most common issues for updating/upgrading issues.!!

# Fixes Issues 
Issues Fixed:

 *   APT Issues:
        Fixes missing packages, dependency errors, and broken installations.
        Automatically updates and upgrades packages.

 *   Broken Installations:
        Resolves packages stuck in installation, removing broken ones and restoring correct versions.

 *   Missing Dependencies:
        Handles missing dependencies in apt package management and repairs system integrity.

 *   APT File Problems:
        Fixes issues with the apt-file tool (used to search for files in packages), purges and reinstalls it.

 *   Checksum Errors:
        Repairs checksum problems by switching to a reliable Kali mirror (NCTU mirror or fallback).

 *   DPKG Issues:
        Fixes dpkg configuration problems and forces the reinstallation of damaged packages.

 *   Downgrading:
        Checks for potential downgrades and applies them safely (for packages that might have upgraded incompatibly).

 *   Kernel Issues:
        Helps resolve kernel version mismatches by removing old kernel versions and installing the newest available one.

 *   GRUB Bootloader Issues:
        Reinstalls and updates the GRUB bootloader after kernel updates or system changes.

 *   System Cleanup:
        Removes unnecessary packages and files using apt autoremove and apt clean, freeing up space and improving performance.

 *   System Health Check:
        Audits the system for package issues and fixes broken dependencies, performing overall system maintenance.

 *   Repository Fix:
        Restores the original Kali Linux repository configuration if the system's /etc/apt/sources.list file is corrupted.

 *   Comprehensive Installation:
        Installs all available Kali tools (kali-linux-everything), ensuring the system has a complete toolkit for penetration testing and security tasks.


Here’s a summary of what the enhanced script does, what issues it fixes, and the new additions:
Issues Fixed:

    APT Issues:
        Fixes missing packages, dependency errors, and broken installations.
        Automatically updates and upgrades packages.

    Broken Installations:
        Resolves packages stuck in installation, removing broken ones and restoring correct versions.

    Missing Dependencies:
        Handles missing dependencies in apt package management and repairs system integrity.

    APT File Problems:
        Fixes issues with the apt-file tool (used to search for files in packages), purges and reinstalls it.

    Checksum Errors:
        Repairs checksum problems by switching to a reliable Kali mirror (NCTU mirror or fallback).

    DPKG Issues:
        Fixes dpkg configuration problems and forces the reinstallation of damaged packages.

    Downgrading:
        Checks for potential downgrades and applies them safely (for packages that might have upgraded incompatibly).

    Kernel Issues:
        Helps resolve kernel version mismatches by removing old kernel versions and installing the newest available one.

    GRUB Bootloader Issues:
        Reinstalls and updates the GRUB bootloader after kernel updates or system changes.

    System Cleanup:
        Removes unnecessary packages and files using apt autoremove and apt clean, freeing up space and improving performance.

    System Health Check:
        Audits the system for package issues and fixes broken dependencies, performing overall system maintenance.

    Repository Fix:
        Restores the original Kali Linux repository configuration if the system's /etc/apt/sources.list file is corrupted.

    Comprehensive Installation:
        Installs all available Kali tools (kali-linux-everything), ensuring the system has a complete toolkit for penetration testing and security tasks.

# New Additions:

  *  NCTU Mirror Check:
        The script now verifies whether the NCTU Kali mirror is available before switching to it. If it’s not, it restores the original repository settings.

  *  Downgrade Detection:
        A new function checks whether any packages require downgrading and performs safe downgrades to fix issues caused by improper package upgrades.

  *  Kernel Fix:
        Added logic to purge outdated Linux kernel versions and install the latest available one, preventing boot or kernel-related problems.

  *  GRUB Update:
        After major updates, especially kernel fixes, the script updates the GRUB bootloader to ensure the system boots with the correct kernel.

  *  System Health Check:
        Added a comprehensive health check routine to audit the system, fix broken packages, and clean up unneeded files for overall system stability.

# Key Features Added:

   * System Repair Options: Multiple repair options for various apt and dpkg issues.
   * Full System Tool Installation: Ability to install all Kali tools at once (kali-linux-everything).
   * Automated Cleanup and Performance Optimization: Removes unneeded packages and updates the system.
   * Enhanced Resilience: Checks mirrors, downgrades packages when necessary, and updates the bootloader after major changes like kernel updates.

`I want to thank Martijn Kamminga, he requested APT-file purge to be added.` 
`Thanks sir `



# Extra Functionality
* Downgrade Functionality 
* Apt Auto Remove Functionality
* Restore Original Kali DEB 

* {!} New option >> Install option to install every possible kali tool 

# For Depracated Depency Issues 
* I advice to run cheksum fix, to sort these issues...  

# For File Size To Large, Wait On Sync... 
* I advice to use option 4 

# Install 
* `chmod +x install`
* `./install`

# Usage
* open terminal and type
* `sl0ppy-KaliFix`
* pick ur fix by enter `1, 2, 3, 4, 5, 6, etc.`

# for other linux dist.
* Edit the Sl0ppy-Kalifix with the right stuff for ur dist.
* Edit the sources.list from kali to ur most recent dist.

For the rest it should work as long u change that..! 


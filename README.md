# Tools

## Description

Compiled binaries of Delphi Worlds companion tools

This project contains tools associated with Delphi Worlds projects and articles published on the Delphi Worlds blog:

  https://www.delphiworlds.com/blog

  **USE THESE TOOLS AT YOUR OWN RISK. NO RESPONSIBILITY WILL BE ACCEPTED FOR LOSS OF DATA, OR ANY OTHER DAMAGE**
  
  **ENSURE YOU HAVE A BACKUP OF ALL CODE AND DATA BEFORE USING ANY OF THESE TOOLS**
  
Where applicable, the source for these tools will eventually be added to a public repository for each tool.


## Android SDK Installer 

For manual install of the Android SDK, focusing on the minimum requirements for use with RAD Studio

## STAR (SDK Transform Assist Resource)

Used for transforming ObjectiveC headers into Delphi (Object Pascal)
  
Usage should be fairly straightforward

## Transferizor

**Experimental - USE AT YOUR OWN RISK**

**Please make a backup of your Delphi registry settings before using the Import function**

### Description

Helps migrate settings/files between updates of Delphi (e.g. between 11.0 and 11.1)

Exports/Imports registry settings, desktop layout files (`.dst`) and connection profile files (`.profile`)

### Basic instructions

Click Export to export settings/files. It will prompt for a folder to save to - this folder will contain the exported registry items and other files

Click Import to export settings/files. It will prompt for a folder which should contain the exported registry and other files. After clicking OK, it will prompt for whether the registry entries should be imported. It will make a backup of any existing `.dst` or `.profile` files that it finds

**Before importing to an update of Delphi, please use RegEdit to export the entire registry entry for that version of Delphi in case the import fails**


  

# Tools
Compiled binaries of Delphi Worlds companion tools

This project contains tools associated with Delphi Worlds projects and articles published on the Delphi Worlds blog:

  http://www.delphiworlds.com/blog

  *** USE THESE TOOLS AT YOUR OWN RISK. NO RESPONSIBILITY WILL BE ACCEPTED FOR LOSS OF DATA, OR ANY OTHER DAMAGE ***
  
  *** ENSURE YOU HAVE A BACKUP OF ALL CODE AND DATA BEFORE USING ANY OF THESE TOOLS ***
  
Where applicable, the source for these tools will eventually be added to a public repository for each tool.

Tools:

STAR (SDK Transform Assist Resource)

  Used for transforming ObjectiveC headers into Delphi (Object Pascal)
  
  Usage should be fairly straightforward. Please create an issue if documentation should be required.
  
Version history:

1.0.0.0
  * Initial release
  

ACTED (Android Companion Tool Enhancing Delphi)

  Used for:
  
  * Extraction of Android Archive (AAR) files, specifically for inclusion of Android libraries such as Firebase
  * Creation of jars that include R classes - again for inclusion of Android libraries
  * Creation of strings.xml from google-services.json for inclusion with Firebase projects
  * Building of jars from Java source for inclusion with Android projects
  
Version history:

1.2.0.0
  * Added Build Jar function
  * Reworked execution of commands to use JvCreateProcess from JVCL
  * Most file/folder selections are now remembered

1.1.0.0
  * Fixed issue with Android SDK Path selection
  * Fixed issue with Android API Level selection
  
1.0.0.0
  * Initial release
  

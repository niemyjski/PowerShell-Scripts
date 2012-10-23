PowerShell-Scripts
==================

Useful PowerShell development scripts

UpdateDart.ps1
==================
This Windows PowerShell script allows you to quickly download and use the latest nightly build of the dart editor.

Please follow the steps below to use this script.
1. Download the UpdateDart.ps1 script.
2. Verify that script execution is enabled on your local machine.
3. Install the latest version (3.0 RC or greater) of PowerShell Community Extensions (http://pscx.codeplex.com/releases/).
4. If you are on a 32 bit operating system, please update the Import-Module path to where Pscx is installed (E.G., Import-Module -Name 'C:\Program Files\PowerShell Community Extensions\Pscx3\Pscx')
5. OPTIONAL: Update the basepath variable (line: ~36) to the folder you wish to install the Dart Editor to. The default is C:\Dart
6. Execute the PowerShell script. 
7. Navigate to the install folder (As described in step 6). This defaults to C:\Dart
8. Launch the downloaded and extracted Dart Application.
# Power Automate Flow to reassign ownership for Power App

This package contains a sample flow that

1.  Is Triggered by an HTML request (for simplicity, this sample uses GET as the request method)
2.  Retrieves all apps from all environments
3.  Reviews the properties for each app
4.  Determines if the app owner is disabled in Office 365
5.  \[If Owner = disabled\] Reassign the app to System Admin
6.  Send email to the Admin making them aware that app ownership was reassigned.

To use this package, download the .zip package and import into your environment. Be sure set variables for Environment Name and Connections during the import.

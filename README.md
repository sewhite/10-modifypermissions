Project user roles extension version 0.2 

# project-user-roles

Shows user roles and permissions for a Paratext 10 project, read from that project's
`ProjectUserAccess.xml`. Built from paranext-extension-template. If the user is an administrator of the project, the roles can
be modified such as changing edit permissions for specific books. 
Major changes like adding or removing users, or modifying a user's role need to be done in the registry, because those changes need to sent directly to the registry, not just changed in the project user access file. The plugin does show a link to the project registration. 

Install this extension by downloading the zip file from the release folder, and copying it to Paratext 10's installed extensions folder. (Currently \C:\Users\_username_\.paratext-10-studio\installed-extensions -- don't overlook the period or full stop at the beginning of the paratext 10 studio folder name) 

Open it from a project's **Project** menu (_Project User Roles..._) or pick a project from the
dropdown.
<img width="481" height="435" alt="image" src="https://github.com/user-attachments/assets/f97a1501-4d41-46c7-bd69-feb0a4c9c6f9" />
 Everyone can view the project's users, roles, book access and permissions. If the
Paratext user registered on this computer is the project's **Administrator**, book access and
permissions become editable. Changes do not take effect until you click the Save button at the bottom of the permissions display. Also at the bottom is a link to the project registration page, where you can add or remove users, or change a user's role. As I said above, these changes need to be sent directly to the registry as well as to the project user roles file. (If the project user roles file and the registry did not agree, Paratext would believe the registry and display a message that the permissions file is out of sync). 



## Template Info

This extension is built from a Webpack project template pre-configured to build a Platform.Bible extension. It includes only the bare essentials required for an extension to work. The template is at https://github.com/paranext/paranext-extension-template


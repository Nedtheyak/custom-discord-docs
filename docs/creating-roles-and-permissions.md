---
layout: default
title: Creating Roles And Permissions For A Server
nav_order: 3
---

# Creating Roles And Permissions For A Server
{: .no_toc }

When in a server community, it is be hard to manage a large amount of users. Server owners and admins probably don't want to allow new members to have the exact same powers as them. Having unchecked powers could make the server subject to griefing and overall damage the community. To circumvent this, Discord has many customizable options to restrict or give access to powers through assigning users roles, giving special permissions and restricting category/channel access.

This section of the documentation will show you how to create roles, what options you can enable/disable, how you can assign roles to users and changing permissions for categories and channels.

## Roles

In a server, roles are often seen as one of the most important tools to enforce server rules and management. It is important to set them up before opening up your server to other users.  

### Navigating The Roles Menu

1. **Open up Discord and navigate to a server that you have administrative powers in, or create a new server.**

    The roles options are within the server settings option, you can access it by clicking the small downwards arrow next to the server name. 

    <img src="https://kaydens.ca/user-docs-discord/assets/images/server_settings.PNG" alt="Server Settings option."/>

2. **Go into the Roles menu by clicking the option in the sidebar.**

Once you've entered the Roles menu, you will see all the information concerning the current roles for the server. Take a moment and look through each of the permissions you can grant. 

Each section in this menu will be explained below.

**Current Roles**

<img src="https://kaydens.ca/user-docs-discord/assets/images/roles_menu_roles.png" alt="Current Roles."/>

Any currently created roles are displayed here. Clicking any one of them will reveal the permissions and customization options for them.

**Role Customization**

<img src="https://kaydens.ca/user-docs-discord/assets/images/roles_menu_customization.png" alt="Customization."/>

This is the customization section for roles. You can change the name, colour and a couple of supplementary options for visual and functional aid.

**Role Permissions**

<img src="https://kaydens.ca/user-docs-discord/assets/images/roles_menu_permissions.png" alt="Permissions."/>

These are the general permissions for the role you've currently selected. There are also text and voice specific permissions. You can grant or restrict them here.

### Adding And Customzing A New Role 

Now onto adding a new role, make sure you have an idea of what roles you want in your server first, and what permissions each one has.

1. **Click the small `+` (plus-sign) symbol at the top right of the roles section.**

    <img src="https://kaydens.ca/user-docs-discord/assets/images/add_new_role.PNG" alt="Add a new role icon."/>

2. **Select the new role and customize it.**

    You will automatically select the new role once it has been created. You can now enable and disable permissions for the new role.

    Here, we give an example of the permissions a regular server member without administrative powers may have.

    <img src="https://kaydens.ca/user-docs-discord/assets/images/test_role_general_permissions.PNG" alt="General Permissions."/>

    These are the general permissions, our user can create invites to invite other users, change their nickname in the server and upload emotes.

    <img src="https://kaydens.ca/user-docs-discord/assets/images/test_role_text_permissions.PNG" alt="Text Permissions."/>

    These are the text permissions, our user can send messages freely, post links and upload files from their device. They cannot freely pin or delete other users messasges though.

    <img src="https://kaydens.ca/user-docs-discord/assets/images/test_role_voice_permissions.PNG" alt="Voice Permissions."/>

    These are the voice permissions, our user can connect to voice channels they have permission to join and speak in them. They cannot mute, deafen or move other members out of the voice channel, however.

3. **Once you're happy with your new role, select the `Save Changes` button at the bottom of the menu to save your changes.**

    <img src="https://kaydens.ca/user-docs-discord/assets/images/save_changes.PNG" alt="Save Changes button."/>

### Giving A Role To A User 

Now that you've created your new role, you can assign it to a user in the server.

1. **Select the user you want given the role and click the small `+` (plus-sign) symbol next to their current roles.**

    <img src="https://kaydens.ca/user-docs-discord/assets/images/select_the_user.PNG" alt="Adding a new role to a user."/>

2. **Search up the role and assign it.**

    We'll be assign this user the `Test Role` we just created/

    <img src="https://kaydens.ca/user-docs-discord/assets/images/adding_role_to_user.PNG" alt="Adding a new role to a user."/>

    After we select the role, it will automatically be added to the user.

    <img src="https://kaydens.ca/user-docs-discord/assets/images/given_test_role.PNG" alt="Adding a new role to a user."/>

    The user will now be given all permissions under the role. If a user has a role that enables some permissions that the role that was assigned to them disables, the permissions will **NOT** be disabled. Role permissions have an upwards hierarchy, the role with the most power will be the prevailing one used for user.

## Categories And Channels

Discord also has an easy way to organize and manage text and voice channels. Categories allow you to group channels for certain topics into easily accessible folders on the side bar. You can grant or restrict permissions for the whole category or on a channel by channel basis.

### Accessing And Changing Permissions

Just like for users, it is possible to change permissions for categories and channels. However, there are a much smaller host of permissions for them.

Since categories and channels share very similar permissions, we will be editing the permissions on a channel. 

1. **Select the channel you want to modify the permissions for.**

<img src="https://kaydens.ca/user-docs-discord/assets/images/edit_channel.PNG" alt="Editing a channel."/>

2. **Select the permissions tab in the channel menu. Add the permissions as needed.**

    You can add permissions based on roles, you can restrict reading and sending messages based on the role a user has. If you create a channel underneath a category, the channel will automatically sync to the permissions of the category first.

    <img src="https://kaydens.ca/user-docs-discord/assets/images/channel_permissions.PNG" alt="Channel options."/>

    As seen in here, it is synced with the `actual-school` category and the only role that the permissions are modified for are for `@everyone`, which all users have. Like creating roles, you can add roles to different permissions for by clicking the small `+` (plus-sign) symbol next to `Roles/Members`. 

    We will now modify some permissions for the channel.

    <img src="https://kaydens.ca/user-docs-discord/assets/images/channel_general_permissions.PNG" alt="General Permissions."/>

    We have changed the general permissions for this channel to disallow invites directly to the channel.

    <img src="https://kaydens.ca/user-docs-discord/assets/images/channel_text_permissions.PNG" alt="Text permissions."/>

    We have also changed the text permissions to disable messages being played in TTS, as well as messages cannot be deleted or pinned by members. Finally, we have disabled pinging to large roles like `@everyone`, `@here` and `@mention` for roles.

3. **Select `Save Changes` once you are done editting your permissions.**

    <img src="https://kaydens.ca/user-docs-discord/assets/images/save_changes_channels.PNG" alt="Save Changes."/>

    Once you've saved your changes, the effects will be applied immediately. 
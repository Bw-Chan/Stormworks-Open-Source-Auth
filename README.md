# Stormworks-Open-Source-Auth

This is the main part of your Server! yay

If you have any issues feel free to contact me, discord: bwchan (I will also keep an eye on the issues stuff but I might be a bit slower to do so since I will probably be doing other things)

Please credit me if you can, if you do not want to then well me big sad.

This handles basic functions like:
- Announcments
- Help <-- might need changes depending on what commands you have in other scripts or this one
- Player Management
- Admin Management <-- you have to configure this in the script (you may do it in your server_config.xml file but this will add them automatically)
- And other Fun Stuff!

## Lets get Started!

To add the script to your server take this folder:

![image](https://github.com/user-attachments/assets/c4f707c2-61f9-4d92-8b05-bc294dc0359c)

and navigate to your `../Steam/steamapps/common/Stormworks`

go into `/rom/data` and place that folder into missions (or create your own folder)

Then in navigate to your server_config.xml (usually in `C:/users/[your_name]/appdata/roaming/stormworks`)

![image](https://github.com/user-attachments/assets/4a31c2e5-bffc-4b07-92b5-11330e35728f)

and specify in the playlist: `<path path="rom/data/[missions or the folder you create]/[stormworks addon name]"/>`
Then you are done! (you will need to do this for every addon/mission you add)

### Configuring your script!
![image](https://github.com/user-attachments/assets/a27edfd1-5c99-4ae9-9ae7-1f7f43b3209b)

This is the start of your config and you can replace all of that however you like.
It seems self explanitory so I wont explain it here.

![image](https://github.com/user-attachments/assets/7b74f4fc-a0af-4ce8-be8f-0a8e8d0ccc8c)

These are your commands (including the vehicle manager I have made (not included here) and the extras inculded with this script)
You can change these depending on what commands you add/change (make sure you keep this up to date it is quite important... duh!).

![image](https://github.com/user-attachments/assets/524492ff-ffca-469d-9b6f-f11406e55288)

These are the second to last parts you can change.
The Announcements are displayed every interval that you specified at the start of the script, You can change this however you like to display any information you feel the user might need.
For instance a message is displayed for your discord link as specified in the info = {} list above.

Rules can be completely re-done if you do not agree or are unhappy with them or leave em if you are lazy and cannot be bothered changing it lol.

As for your admins,

The format goes like this:
`
admins ={
  {"admin1",steam_id},
  {"admin2",steam_id}
}
`
As for getting the steam_id go to [Steamid.io](https://steamid.io) and put their username in OR
if their steam profile url looks like this: ![image](https://github.com/user-attachments/assets/6af2e3d4-236e-44d0-9b00-82c31e7c104d)
Then it is pretty much already there for you :P

![image](https://github.com/user-attachments/assets/43e42dba-f330-45a5-b8f7-06e09406382a)

And then we have these commands for your admins!
Change this depending on what admin commands you decide to add or remove.

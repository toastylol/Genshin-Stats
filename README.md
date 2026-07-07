# genshin stats!
a discord widget for your genshin stats using [enka](https://enka.network/)!

please star the repo if you like it :p it motivates me to make more stuff like this

<div align="center">
<img width="359" height="230" alt="widget addition" src="https://github.com/user-attachments/assets/829b0a59-67a9-4b7b-91c3-7f21e3d805ca" />
<img width="352" height="251" alt="main widget" src="https://github.com/user-attachments/assets/f7cc013b-62d2-4ece-97fd-b227ed40e062" />
<img width="227" height="80" alt="mini view" src="https://github.com/user-attachments/assets/efdbea80-00a1-4ff6-8e58-343f7e717e4b" />
</div>

special thanks to @chloecinders, @aamia, @bignutty and @.dziurwa and the rest of the smart people at [discord previews](https://discord.gg/discord-603970300668805120) for getting out the first info on these.
# how to use?

### be advised that this requires knowing what you're doing, along with browser devtools knowledge!
> this warning only applies if you are manually creating your widget!
- 1a. use this [widget creation script](https://gist.github.com/aamiaa/7cdd590e3949cd654758bc90bcb4710b) by aamia. skip steps `1b` and `iv` if you are using this.
- 1b. if you want to manually go thru the creation process, follow the steps in this [blog post](https://chloecinders.com/blog/discord-widgets) by chloecinders to create your discord application, social sdk profile and widget design. 
- your widget design must be as follows for the widget to show data properly (you can add sample data in the widget editor to preview how it will look):


| <img width="1047" height="261" alt="image" src="https://github.com/user-attachments/assets/0e054412-7359-48dd-87b6-5443856f7bb7" /> | <img width="1045" height="257" alt="image" src="https://github.com/user-attachments/assets/5d44707e-cf5d-4b99-9544-26bcde395aa3" /> |
| :---: | :---: |
| <img width="1047" height="259" alt="image" src="https://github.com/user-attachments/assets/42cb5ad3-3088-4461-8f1f-5b34986a31a1" /> | <img width="1046" height="263" alt="image" src="https://github.com/user-attachments/assets/2738e778-bf8d-4677-bde7-e6bf0e81a19a" /> |

- 2. clone this repo and create a .env file with your `GENSHIN_UID`, `DISCORD_BOT_TOKEN`, `DISCORD_USER_ID` and `DISCORD_CLIENT_ID`
- 3. run `node enkaUser.js` to sync your genshin stats to discord thru [enka](https://enka.network/).
- 4. use a snippet from [discord previews server (linked above)](https://discord.com/channels/603970300668805120/1509942620762276011) to add it to your profile!
----
if you wish to update your stats, just run the program again.

alternatively, you can use [windows task scheduler](https://www.technipages.com/scheduled-task-windows/) or [systemd](https://www.funwithlinux.net/systemd-service-management/streamline-your-workflow-with-systemd-s-automation-features/) on linux or [use launchd](https://blog.serghei.pl/posts/scheduling-recurring-tasks-on-macos-using-launchd/) on macos to automate the process!

# Jr's Utilities Mod Help
As said, there are commands that help moderate and manage this server. Make sure to punish people correctly and read the `#mod-guide` channel :)

*\*This is also a slash command with Jr's Utilities!*

> _Legend:_
> ```
> - <required>
> - [optional]
> ```
  
## Moderation 🛠️
  
### `jr!modnick`
This command will moderate out someone's display name/nickname if it is disturbing in chat.
  
> _Usage:_
> ```
> jr!modnick <@<userID>>
> ```
  
### `jr!warn`
This command will warn the mentioned user with the reason argument you must provide when doing so and vice versa.
  
> _Usage:_
> ```
> jr!warn @<user> <reason>
> ```

### `jr!timeout`
This command will timeout the mentioned user for a given number in minutes with the reason argument you must provide when doing so and vice versa.
  
> _Usage:_
> ```
> jr!timeout <number in minutes> @<user> <reason>
> ```

### `jr!untimeout`
This command will untimeout the mentioned user.
  
> _Usage:_
> ```
> jr!untimeout @<user>
> ```
  
### `jr!kick`
This command will kick the mentioned user with the reason argument you must provide when doing so and vice versa.
  
> _Usage:_
> ```
> jr!kick @<user> <reason>
> ```
  
### `jr!ban`
This command will ban the mentioned user with the reason argument you must provide when doing so and vice versa.
  
> _Usage:_
> ```
> jr!ban @<user> <reason>
> ```
  
### `jr!resetwarn`
This command will reset and clear the user's warnings.
  
> _Usage:_
> ```
> jr!resetwarn @<user>
> ```
 
## Management 🔧
  
### `jr!slowmode`
This command will set the slowmode in the amount of seconds as the number argument in the channel the user used the command in.
  
> _Usage:_
> ```
> jr!slowmode <seconds>
> ```
  
### `jr!lock`
This command will lock the channel the user used the command in with a reason argument you must provide.
  
> _Usage:_
> ```
> jr!lock <reason>
> ```
  
### `jr!unlock`
This command will unlock the channel the user used the command in.
  
### `jr!giverole`
This command will give a role argument to the mentioned user argument.
  
> _Usage:_
> ```
> jr!giverole @<user> <roleID>
> ```
  
### `jr!takerole`
This command will take away a role argument from the mentioned user argument.
  
> _Usage:_
> ```
> jr!takerole @<user> <roleID>
> ```
  
### `jr!createrole`
This command will create a role for the following required arguments:
- `Role Name` (no spaces)
- `Role Hex Color`
- `Hoisted` (yes/no)
- `Mentionable` (yes/no)
  
> _Usage:_
> ```
> jr!createrole <role-name> <hexcolor> <hoisted(yes/no)> <mentionable(yes/no)>
> ```
  
### `jr!delrole`
This command will deletey a role argument from the server.
  
> _Usage:_
> ```
> jr!delrole <roleID>
> ```
  
### `jr!rule`*
This command returns the rule with the rule number being an argument.
  
> _Usage:_
> ```
> jr!rule <rulenumber>
> ```
  
### `jr!faq`*
This command returns the FAQ with the FAQ number being an argument.
  
> _Usage:_
> ```
> jr!faq <rulenumber>
> ```
  
## Admins 👨‍💻
  
### `jr!pingdeadchat`
This command will delete your command message and use the `Dead Chat Ping` role to try and revive the channel the user uses the command in.
  
> # More commands in the future!
> _~Jryptix (bot creator)_

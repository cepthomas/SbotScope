# What It Is

Similar to builtin ST commands with enhancements - shows scope stack with color and style for current selection or
all common ones. Useful for figuring out color-schemes.

Built for ST4 on Windows and Linux.

Requires [SbotCommon](https://github.com/cepthomas/SbotCommon) plugin.

## Commands
| Command                  | Implementation | Description                                              | Args         |
| :--------                | :-------       | :-------                                                 | :--------    |
| sbot_show_scopes         | Context        | Popup that shows style for all common scopes             |              |
| sbot_scope_info          | Context        | Like builtin show_scope_name but with style info added   |              |

## Settings
| Setting              | Description                                        | Options   |
| :--------            | :-------                                           | :------   |
| scopes_to_show       | List of scope names for sbot_show_scopes command   |           |

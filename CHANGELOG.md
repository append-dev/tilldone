# Changelog

What each release of Tilldone brings, newest first.

## 0.0.1

The first release: your Mac kept awake till your agents are done.

- **An MCP server for your agents** (`tilldone mcp`): `hold`, `release` and `status`. A hold lasts till released or for some minutes, keeps the display on if asked, and ends with the agent's session, however it ends.
- **A menu bar app** that opens on its own the first time anything asks it to hold. It shows what holds the Mac and why, keeps it awake by hand (till released, or for 15 minutes to 8 hours), and releases one hold or all. Each line has its icon, drawn for a light or a dark menu bar.
- **About and Settings**: open at login, the command that gives Tilldone to Claude Code, the command line, and whether Plugate's plugin is installed.
- **`tilldone run -- <command>`**: your Mac kept awake while a command runs, and free the moment it ends, however it ends. The command keeps the terminal; the run ends with its code.
- **A command line**: `tilldone hold`, `release` and `status`, the same sentences as the menu's.
- **Plugate's plugin**: holds the Mac while Plugate's agents work, and lets it go a few minutes after the last is done.
- On npm as `tilldone`, for Macs with Apple silicon and with Intel, free to use.

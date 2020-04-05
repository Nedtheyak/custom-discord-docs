---
layout: default
title: Setting Up A Discord Bot On A Server
nav_order: 2
---

# Setting Up A Discord Bot On A Server
{: .no_toc }

Bots are great as a regular point of discussion, or a means of moderating your server. They can help keep your server under control, and can have fun activities. In this guide, we will show you how to add a bot to your server and get it set up.

We will start with general instructions for getting a bot on your server, and then walk you through setting up some popular bots.

1. TOC
{:toc}

## Inviting a Bot

1. **Select a bot to add.**

    You'll need to choose a bot to match your purposes. Bot list websites like [top.gg](https://top.gg/) can help you find one easily. For the sake of this guide, we'll be using the multi-purpose bot [UnbelievaBoat](https://unbelievaboat.com/).

    <img src="https://kaydens.ca/user-docs-discord/assets/images/note.png" alt="Note." style="height: 50px"/> **Note:** Mark down the website where you find this link or button, it may have useful information or troubleshooting help related to your particular bot.

2. **Find the bot's invite link.**

    You'll need to find and click the link to invite the bot to the server. If your bot is from [top.gg](https://top.gg/), the bot's page will have a clearly marked *`Invite`* button:

    <img src="https://kaydens.ca/user-docs-discord/assets/images/topgg_invite_button.png" alt="Bot invite button on the website top.gg from main bot page" style="height: 220px" />

    If you are looking at a custom website for a bot, look for and click a button or link labelled *`Invite to Discord`*, "Add to Server," or similar phrases. Here's an example:

    <img src="https://kaydens.ca/user-docs-discord/assets/images/invite_to_discord_button.png" alt="Example of a button to invite a bot. Text: Invite to Discord" style="height: 50px" />

3. **Select your target server.**

    You should be brought to a page a panel like this. Select your desired server from the dropdown menu, and click *`Continue`*.

    ![Discord "Invite to server" panel for adding bots to servers. Interactable text: Select a server, cancel, continue](https://kaydens.ca/user-docs-discord/assets/images/invite_to_server_panel.png)

    <img src="https://kaydens.ca/user-docs-discord/assets/images/note.png" alt="Note." style="height: 50px"/> **Note:** If you choose not to provide certain permissions, the bot's functionality may be limited.
4. **Select appropriate permissions.**

    To finish inviting the bot to your server, you may be prompted to provide it with permissions. 

    If you want to change these permissions later, see our section on [Roles and Permissions](https://kaydens.ca/user-docs-discord/docs/creating-roles-and-permissions/).

5. **Check that the bot has joined.**

    You should see the bot in your member list on the right. 

## Setting Up the Bot

{:start="6"}
6. **Follow the bot's instructions (if applicable).**

    Some bots have a setup process that starts upon inviting the bot. Follow its instructions before continuing.

7. **Find the command prefix.**

    While this can differ between bots, you can usually `mention` the bot using the `@` symbol, followed by a space and your command, and it should respond.

    Bots typically have a `prefix` command; you should be able to use that to discover and/or set the prefix.

8. **Explore the bot's functionality.**

    Each bot will work differently, so make sure to explore what's available. Almost every bot has a `help` command, so invoke that using the prefix you found in step 7.

    For example, if the prefix is `!`, you could send this message:
    ```
    !help
    ```
    Many bots will also support this standard help command syntax:
    ```
    help [command name]
    ```
    For example, if you wanted more information about the `prefix` command, for a bot that uses the prefix `!`, you might send this message:
    ```
    !help prefix
    ```


If your bot's responding and interacting as intended, you should now be ready to use your bot! 

For further information and/or instruction, you may wish to refer to any webpages dedicated to it. Where applicable: its [top.gg](https://top.gg/) page, a dedicated website (usually available via the `help` command), or its own Discord server. The webpage you noted down in step 2 may also prove helpful for this.

## Troubleshooting
If your bot is not responding as expected, here are some tips for reasonable measures.
    
1. **Give the bot some time to respond.**

    Be patient. Give it a minute, then try your command again.

    If the bot is offline, give it 5-10 minutes to come back online. 

2. **Check your syntax (prefix, command name).**

    It may sound silly, but check for typos in your message. Make sure you're using the right prefix. Maybe even try a different command that you used earlier, which you know should work.

3. **Check their website.**

    Check the bot's website for information about potential downtime or recent changes, if available.

4. **Check their Discord server.**

    Look in the support server for the bot. See if there is anyone asking about the same problem, or if there are any recent messages from staff regarding this issue.

    <img src="https://kaydens.ca/user-docs-discord/assets/images/warning.png" alt="Caution." style="height: 50px"/> **Caution**: Be very polite, and be careful not to mention (with the `@` symbol) people about your issue unless they explicitly ask for it. Your issue may be timely, but mentioning them will likely only annoy them. Follow their rules carefully, and you are much more likely to be helped.

5. **Ask for help from staff.**

    Humbly ask for help in their Discord server (or any other platform, if available). Ideally you will get an accurate response from a staff member, but often the community can help, as well. Be open to hearing advice from anyone.

6. **Investigate other options.**

    If you still can't get the bot to work, search for alternatives. Many bots serve the same purpose, so if possible, search websites like [top.gg](https://top.gg/), or simply through your search engine. 
    
    Sometimes users your original bot's Discord server will have suggestions about alternatives too, but be wary of angering their community members. Many staff members or community members might be quite partial to this bot, and asking for alternatives within their server can be quite disrespecful. When in doubt, just do your own research.

<!--
<button style="color: black" onclick="toggleSpoiler('test')">Show/Hide Images</button>
<span id='test' style='display: none'>hi</span>

<script>
function toggleSpoiler(tagId) {
    let targetSpoiler = document.getElementById(tagId);
    if (targetSpoiler.style.display == 'none') {
        targetSpoiler.style.display = 'inherit';
    } else if (targetSpoiler.style.display == 'inherit') {
        targetSpoiler.style.display = 'none';
    }
}
</script>
-->

# Sanderling

**Sanderling helps you read information from the [EVE Online](https://www.eveonline.com) game client.**

Sanderling is the *eyes* of bots and monitoring tools. It helps programs *see* the game client in a structured way, detecting objects and reading information about the game world. It also reads the locations of elements in the game clients' graphical user interface (e.g., in-game windows, overview entries, buttons, etc.). You can use this information to interact with the game client using mouse input.

## Features

+ **safe**: does not inject into or write to the EVE Online client. That is why using it with EVE Online is not detectable.
+ **accurate & robust**: Sanderling uses memory reading to retrieve information about the game state. In contrast to screen scraping, this approach won't be thrown off by a noisy background or non-default UI settings.
+ **comprehensive**: Sanderling is used to build [mining](https://github.com/Viir/bots/blob/master/guide/eve-online/how-to-automate-mining-asteroids-in-eve-online.md), trading, mission running and [anomaly ratting](https://github.com/botengine-de/A-Bot) bots.

## Requirements

+ The application requires Microsoft .NET Framework 4.6.1 which can be downloaded from [https://www.microsoft.com/download/details.aspx?id=49982](https://www.microsoft.com/download/details.aspx?id=49982).

## Where are the Bots?

Some bots using Sanderling:

+ Warp-To-0 Autopilot: [https://github.com/Viir/bots/blob/master/guide/eve-online/how-to-automate-traveling-in-eve-online-using-a-warp-to-0-autopilot.md](https://github.com/Viir/bots/blob/master/guide/eve-online/how-to-automate-traveling-in-eve-online-using-a-warp-to-0-autopilot.md)

+ Mining asteroids: [https://github.com/Viir/bots/blob/master/guide/eve-online/how-to-automate-mining-asteroids-in-eve-online.md](https://github.com/Viir/bots/blob/master/guide/eve-online/how-to-automate-mining-asteroids-in-eve-online.md)

+ [List of EVE Online Bots for Beginners](https://forum.botengine.org/t/list-of-eve-online-bots-for-beginners/629)

+ Most up-to-date: [https://botcatalog.org/](https://botcatalog.org/)

## Feedback

Spotted a bug or have a feature request? Post on the [forum](https://forum.botengine.org) or file an issue [on GitHub](https://github.com/Arcitectus/Sanderling/issues).

## Need Help?

Do you have a question or need help with the development of your bot? Get in contact with other developers on the [BotEngine Forum](https://forum.botengine.org).

## Information For Developers

### Bot Creators

This is a list of guides and resources for bot developers:

+ An easy way to explore the Sanderling framework, test memory reading and sending input to the game is the [BotEngine Windows Console](https://to.botengine.org/guide/windows-console).
+ Terplas [beginners guide for botting in EVE Online](https://forum.botengine.org/t/terpla-adventures-or-blog-style-guide-for-begginers/953)
+ [Explaining the different types of memory readings](https://forum.botengine.org/t/sanderling-framework-differences-between-memorymeasurement-memorymeasurementparsed-and-memorymeasurementaccu/1256)
+ [How to Select a Target](https://forum.botengine.org/t/how-to-select-a-target/600)
+ [How to Activate a Ship Module](https://forum.botengine.org/t/how-to-activate-a-ship-module-in-eve-online/602)

### Building from source
The source code uses C# 7 features. It is recommended to use [Visual Studio](https://www.visualstudio.com/) version 2017 or newer for building.

## Contributing

### Tutorials and Guides

People share their tutorials and guides in the [*Show and Tell* section on the BotEngine Forum](https://forum.botengine.org/c/show-and-tell). Add the [`guide`](https://forum.botengine.org/tags/guide) tag to your post for best visibility.

### Issues

For communication here, supported languages are English, Spanish, and German.

### Pull Requests

The only supported language for pull request titles and commit messages is English.

At the moment, automation to compare the usefulness of scripts for the userbase is not ready. This means that evaluating changes to scripts included in the master branch can require much effort.    
In case you propose a change to a script in the master branch, it is recommended to get feedback from other users.


<br><br><br><br>

![Visualization of data read from the EVE Online client memory.](image/uitree.extract.png)

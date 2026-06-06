# TradeTrace

TradeTrace is a plugin for Paper that helps you keep track of what player are buying and selling. It also looks at what people are doing when they resell things on different marketplaces.

## Features

* You can track when people buy things from:

* QuickShop

* Shopkeepers

* AuctionHouseRewrite

* It can automatically find out when someone is reselling things.

* You can see where the things that someone is reselling came from.

* You can look at a persons reselling history. See where they source their inventory.

* You can reset players reselling history if you need to.

* You can change the messages that the plugin sends to make them say what you want.

* It supports colors in a format (`&#RRGGBB`).

* You can reload the plugins settings without having to restart the server.

* TradeTrace works with any economy system, including Vault, diamonds, custom currencies, and more!

## Commands

| Command                           | Description                       |

| --------------------------------- | --------------------------------- |

| `/reseller [player]`              | Look at players reselling report |

| `/resellerdetails <player>`       | Look at players reselling statistics |

| `/resellerlist`                   | List all resellers |

| `/resellerreset <player> confirm` | Reset players reselling history            |

| `/tradetrace help`                | Show the help menu                    |

| `/tradetrace info`                | Show information about the plugin           |

| `/tradetrace version`             | Show what version of the plugin you are using |

| `/tradetracereload`               | Reload the plugins settings and messages        |

## Permissions

| Permission         | Description                    |

| ------------------ | ------------------------------ |

tradetrace.admin` | You can use the special commands |

## Configuration

### config.yml

This is where you put the general settings for TradeTrace.

### messages.yml

This is where you can change the plugins messages.

TradeTrace supports:

* Minecraft color codes

* Birdflop hex colors

For example:

```yaml

header: ". #FFD700TradeTrace"

```

## Supported Plugins

* QuickShop

* Shopkeepers

* AuctionHouseRewrite

## Installation

1. Stop your server.

2. Put TradeTrace.jar in the plugins folder.

3. Start the server.

4. Change config.yml and messages.yml to your server needs.

5. Use `/tradetracereload` after you make changes.

## 💡 Support

If you run into issues:

* Double check your config
* Ensure no duplicate plugin jars exist
* Review console errors carefully
* Contact us for any errors
* Contact us to request for more integrations!

---

## 🐝 Buzzle’s Hive

Built as part of the Buzzle’s Hive ecosystem.
Focused on performance, simplicity, and clean server experiences.

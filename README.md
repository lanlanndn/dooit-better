![DOOIT](imgs/banner.png)

# Dooit ✔️
*A todo manager that you didn't ask for, but needed !*

[![Wiki](https://img.shields.io/badge/Wiki-Dooit-white?style=flat-square)](https://dooit-org.github.io/dooit/)
![PyPI Downloads](https://static.pepy.tech/badge/dooit)
[![GitHub issues](https://img.shields.io/github/issues/dooit-org/dooit?color=red&style=flat-square)](https://github.com/dooit-org/doit/issues)
[![GitHub stars](https://img.shields.io/github/stars/dooit-org/dooit?color=green&style=flat-square)](https://github.com/dooit-org/doit/stargazers)
[![Support Server](https://img.shields.io/discord/989186205025464390.svg?label=Discord&logo=Discord&colorB=7289da&style=flat-square)](https://discord.gg/WA2ER9MBWa)

-----------------------------

> [!NOTE]
> **This is a fork** — [dooit-better](https://github.com/lanlanndn/dooit-better) — of [dooit](https://github.com/dooit-org/dooit) (MIT).
> It adds one feature on top of v3.3.4: **completed tasks are rendered with a strikethrough**, so they stand out from pending ones.
> To opt out, disable the formatter in your `config.py`:
>
> ```python
> from dooit.ui.api import DooitAPI, subscribe
> from dooit.ui.api.events import Startup
>
> @subscribe(Startup)
> def _disable_strike(api: DooitAPI, _):
>     api.formatter.todos.description.disable("strike_completed")
> ```

-----------------------------

For installation and configuration, check out [the wiki](https://dooit-org.github.io/dooit/)

# Features 🌟

- An interactive & beautiful UI
- Fully customizable, you can configure your bar, your colors and how everything is displayed!
- Extensible, python config file allows you to do as much as you like!
- Vim like keybindings
- Topicwise separated Todo Lists (With branching)

**Note: See [CHANGELOG.md](CHANGELOG.md) to get more details on changes and feature additions!**

# Usage and configuration :gear:
After launching the app, You can press the `?` key to know the keybindings!

# Screenshots 🖼️

> [!NOTE]
> The configurations below heavily use [Dooit Extras](https://github.com/dooit-org/dooit-extras)

Some screenshots of app with different customized configuration <3

<details>
  <summary>An icy configuration based on NordTheme ❄️ </summary>
  
![Preview 1](./imgs/config1.png)

</details>

<details>
  <summary>A colorful configuration based on Catpuccin 🐱 </summary>
  
![Preview 2](./imgs/config2.png)

</details>

<details>  
  <summary>A calm configuration based on Everforest 🌲 </summary>
  
![Preview 3](./imgs/config3.png)

</details>


# Contribution 🤝
- Want to contribute? Feel free to open a PR! 😸
- Got some ideas for improvements? I'm all ears! 👂
- If you have an idea that related to customizability, open an issue at [Dooit Extras](https://github.com/dooit-org/dooit-extras/issues/new) instead

----------------------------

#### Other TUI projects 🤓 :
If you liked dooit then you might wanna try out some of my other TUI projects as well
- [smassh](https://github.com/kraanzu/smassh) - A typing-test app for terminal

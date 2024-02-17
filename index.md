---
layout: default
title: "Ian's Site"
---

## Tools I like, and even some that I pay for! 

### Grammarly - [grammarly.com](https://grammarly.com)
I pay $144 a year for Premium and use it every day. I primarily use it in Gmail, Notion, Slack, and HubSpot. It works well with local clients and web clients. I wish Grammarly had native Vim support, and I may have missed something to configure it, so for now, I use Vale as my style-enforcer and then fix up things like tone, grammar, and clarity with the Grammarly web editor.

### Vale - [vale.sh](https://vale.sh/)
I use Vale inside Vim as my primary helper for technical writing. Even if Grammarly had some native Vim support, I would still need Vale in my workflow. I have various Vale checks configured to run each time I `:w` text and Markdown files:

  ```
  " .vimrc

  " see ~/.vale.ini for filetype and extension details,
  " i.e., only run certain style-checks on certain filetypes.
  au BufWritePost *.MD !vale %
  ```

Most documentation I write takes place inside Vim. Since the audience for that documentation will be technical readers, Vale is the correct tool for the job because I use the ecosystem of extensions to keep my style consistent.

### Little Snitch - [obdev.at](https://www.obdev.at/products/littlesnitch/index.html)
I pay for Little Snitch and Micro Snitch to monitor my machines' connections to the outside world on the public Internet.

### ScreenFlow - [telestream.net](http://www.telestream.net/screenflow/overview.htm)
I pay for ScreenFlow and have found it useful in recording myself doing demos and editing videos for customers.

### Sidekick - [sidekick.com](https://www.meetsidekick.com/)
I do not pay for Sidekick, but I've considered it several times. Seeing the value in a Chromium wrapper is easier if you use dozens of SaaS tools daily. It's mostly to use something other than pinned tabs for things like Gmail, Gcal, and HubSpot.

### Pitch - [pitch.com](https://pitch.com/)
I do pay for Pitch. It is much better than the typical slideshow apps installed on your OS. They have a unique onboarding flow; you can collaborate with your team via a workspace, but once you decide to upgrade to pro, you'll need a license for everyone in your workspace. 

### Kap [getkap.co](https://getkap.co/)
Kap is great for recording short snippets, whereas ScreenFlow is more for presentations. [Here's an example](https://medium.com/@iangrunt/a-visual-checklist-for-writing-production-grade-terraform-modules-42f092fa7071) where I used it. 

### SFMono NerdFont [github.com/epk/SF-Mono-Nerd-Font](https://github.com/epk/SF-Mono-Nerd-Font)
I still use the regular old Terminal.app with this and `zsh`. 

### UTM [getutm.app](https://getutm.app/)
I adore UTM. 

From [https://github.com/utmapp/UTM/blob/main/README.md](https://github.com/utmapp/UTM/blob/main/README.md)
>>It is possible to invent a single machine which can be used to compute any computable sequence.
>>
>>-- Alan Turing, 1936
>
>UTM is a full featured system emulator and virtual machine host for iOS and macOS. It is based off of QEMU. In short, it allows you to run Windows, Linux, and more on your Mac, iPhone, and iPad

## Tools I use that need no introduction 
I use HubSpot, Notion, 1Password, and Gong, and I enjoy them all!

## Tools I've failed at using

### Gitkraken [gitkraken.com/](https://www.gitkraken.com/)
I do love this tool; I just don't work in an environment that requires it. Helpful when needed to visualize changes and is highly recommended. 

### VSCode/Astrovim
I tried!

### Amethyst - [ianyh.com](https://ianyh.com/amethyst/)
I could not find a use for this window manager (or any window manager). The native Mac OS window-splitting and multiple desktops functionality has worked best for me.

### Obsidian - [obsidian.md](https://obsidian.md/)
Obsidian is a great note-taking tool, but this minor Vim annoyance has prevented me from fully adopting it: https://forum.obsidian.md/t/vim-o-and-o-should-respect-understand-current-context/48386.

## Tools I no longer use

### Alfred - [alfredapp.com](https://www.alfredapp.com/)
I don’t pay for Alfred, and I’m still on Alfred 4, but it is a beautiful tool. The free version lets you quickly query websites, like GitHub.com and others, all from the keyboard.

The "Web Search" feature is included for free and allows me to do things like search the Gruntwork Knowledge Base quickly. For example, my shortcut in Alfred for that specific usage is configured like this:

  ```
  https://github.com/gruntwork-io/knowledge-base/discussions?discussions_q={query}
  ```

And is assigned the keyword `kb`. So I can hit `option+space`, type `kb `, and then whatever terms I want to query, like "EKS." The search term appends to that URL I configured in place of `{query}`  and will bring me directly to the search results. Multiply this by every website you have to type keywords into a search bar for, and you'll begin to love the experience.

### Oxford English Dictionary - [oed.com](https://www.oed.com/)
I pay for Oxford English Dictionary access to confirm I correctly use words with multiple definitions and interpretations.

### Lens [k8slens.dev](https://k8slens.dev/)
I do not pay for Lens, but I would definitely consider it if I were on a team with many Kubernetes clusters. 

### Cron - [cron.com](https://cron.com/)
Cron is currently invite-only, but it has been a good tool for a calendar client over the Google Calendar website. I hope they begin working on an email client because I miss the Outlook on Windows experience.
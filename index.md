---
layout: default
title: "Ian's Site"
---

## Tools

### Grammarly - [grammarly.com](https://grammarly.com)
I pay $144 a year for Premium and use it every day. I primarily use it in Gmail, Notion, Slack, and HubSpot. It works well with local clients and web clients. I wish Grammarly had native Vim support, and I may have missed something to configure it, so for now, I use Vale as my style-enforcer and then fix up things like tone, grammar, and clarity with the Grammarly web editor.

### Vale - [vale.sh](https://vale.sh/)
Even though Grammarly doesn't work with Vim, I continue to use Vale as my primary helper for technical writing. I have it configured to run each time I write on text and Markdown files:

  ```
  " .vimrc

  au BufWritePost *.MD !vale %
  ```

Most documentation I write takes place inside Vim. Since the audience for that documentation will be technical readers, Vale is the correct tool for the job because I use the ecosystem of extensions to keep my style consistent.

### Alfred - [alfredapp.com](https://www.alfredapp.com/)
I don't pay for Alfred, and I'm still on Alfred 4, but it is a beautiful tool. The free version allows you to intuitively query websites, like GitHub.com and others, all from the keyboard.

The "Web Search" feature is included for free and allows me to do things like search the Gruntwork Knowledge Base quickly. For example, my shortcut in Alfred is configured like this:

  ```
  https://github.com/gruntwork-io/knowledge-base/discussions?discussions_q={query}
  ```

And is assigned the keyword `kb`. So I can hit `option+space`, type `kb `, and then whatever terms I want to query, like "EKS." The search term appends to that URL I configured in place of `{query}`  and will bring me directly to the search results. Multiply this by every website you have to type keywords into a search bar for, and you'll begin to love the experience.

### Oxford English Dictionary - [oed.com](https://www.oed.com/)
I pay for Oxford English Dictionary access to confirm I'm correctly using words with multiple definitions and interpretations.

### Little Snitch - [obdev.at](https://www.obdev.at/products/littlesnitch/index.html)
I pay for Little Snitch and Micro Snitch to monitor my machines' connections to the outside world on the public Internet.

### ScreenFlow - [telestream.net](http://www.telestream.net/screenflow/overview.htm)
I pay for ScreenFlow and have found it satisfactory in recording myself doing demos and editing videos for customers.

### Cron - [cron.com](https://cron.com/)
Cron is currently invite-only, but it has been a good tool for a calendar client over the Google Calendar website. I hope they begin work on an email client, because I do miss the Outlook on Windows experience.

### Sidekick - [sidekick.com](https://www.meetsidekick.com/)
I do not pay for Sidekick, but I've considered it several times. Seeing the value in a Chromium wrapper is easier if you use dozens of SaaS tools daily. It's mostly to use something other than pinned tabs for things like Gmail, Gcal, and HubSpot.

# Write it down once: giving DevRel agents the context they keep asking for

- **Speaker:** Marcos Placona, DevRel Bridge
- **Date:** Wednesday, January 13, 2027, 13:00 UTC
- **Format:** Show and tell, 15 minutes
- **GitHub:** [@mplacona](https://github.com/mplacona)

## Abstract

Every agent doing DevRel work, whether it's writing a quickstart, a launch post, or docs, starts by asking who the product is for and what success looks like, and each one gets a different answer.

I'll show an open-source pattern I've been building. You record that context once, in a Markdown file in the repo, in developer funnel terms: who the product is for, time to Hello World, what activation means, and which stage of the journey is broken.

Reusable agent skills then read the file before they audit a quickstart or check whether agents can use your docs. Live demo on a real quickstart, plus what didn't work and what I changed because of it. People will leave with a pattern they can copy into their own repos, whatever agent they use.

## Tools and topics

Claude Code, Codex, and Cursor (any agent that can read a file or fetch a URL), and agent skills that can be installed into any of them. The agent drafts the context file and runs the audits on its own. A person reviews who the product is for and what counts as success, and picks which fixes to ship.

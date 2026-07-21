---
title: "A MCP for Fortra FIM (Tripwire Enterprise)"
date: 2026-07-21
tags:
  - Tripwire Enterprise, TE, FIM, MCP, AI, LLM
---
I've gotten bored of how many times people have asked me about TE AI (LLM) integrations at this stage, so I put a basic one together here: [GitHub - askjarv/fim-mcp: A MCP for Fortra FIM/Tripwire Enterprise][https://github.com/askjarv/fim-mcp] during a quiet five minutes

If you want to give it a go against your TE, effective you just need to download and unzip the repo, install python (latest version should be fine) and then follow the setup details in the readme.md file. 

Here's some conversations I've used to test it this morning to give an idea of what you can do:
Get a list of nodes in your environment:
[![](images/Screenshot 2026-07-21 094653.png)](images/Screenshot 2026-07-21 094653.png)
Get a list of policy test failures:
[![](images/Screenshot 2026-07-21 094653.png)](images/Screenshot 2026-07-21 094653.png)

Finds the hash of a file in the environment:
[![](images/Screenshot 2026-07-21 094701.png)](images/Screenshot 2026-07-21 094701.png)

Promote an element version:
[![](images/Screenshot 2026-07-21 094709.png)](images/Screenshot 2026-07-21 094709.png)

Review my allowlisting:
[![](images/Screenshot 2026-07-21 094644.png)](images/Screenshot 2026-07-21 094644.png)

and, from there, you LLM can start giving your graphics:
[![](images/Screenshot 2026-07-21 092924.png)](images/Screenshot 2026-07-21 092924.png)


It's a bit rough around the edges (it needs more robust tool definitions and limitations to be more effective/token efficient), but I'm curious if others have been experimenting in this space yet or had ideas of use cases that they'd want "built out" more?
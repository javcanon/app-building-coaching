# Step 3: Install Claude Code and Say Hello

_You have a GitHub account (Step 1) and VS Code (Step 2). Now we add the AI coding partner
that will do most of the actual writing: **Claude Code**. This step is just about installing it
and having your first small conversation with it. Still gentle, still no real project yet._

## What is Claude Code?

**Claude Code** is an AI assistant that works inside your project. You describe what you want
in plain English ("make a simple webpage that says hello"), and it writes the files, explains
what it did, and can even commit and push to GitHub for you.

Think of it as a very capable junior developer who sits next to you, does the typing, and never
gets tired of your questions. You stay in charge, it does the heavy lifting.

## A gentle heads-up: the "terminal"

Claude Code runs in a **terminal** (also called a command line), a text window where you type
commands instead of clicking buttons. This can feel intimidating at first, but you only need a
handful of commands, and VS Code has a terminal built right in so you never leave your workbench.

You are not expected to memorize anything. Copy, paste, press Enter. That's it.

## Prerequisite: install Node.js

Claude Code needs a free helper program called **Node.js** installed first.

1. Go to **https://nodejs.org**.
2. Download the version labeled **LTS** (Long Term Support, the stable one).
3. Install it like any normal app (defaults are fine).

That's a one-time setup you won't have to think about again.

## Open the terminal in VS Code

1. Open VS Code.
2. In the top menu, click **Terminal**, then **New Terminal**.
3. A panel opens at the bottom. That's your terminal. You'll type into it.

## Install Claude Code

In that terminal, type this line and press **Enter**:

```
npm install -g @anthropic-ai/claude-code
```

- `npm` is a tool that came with Node.js; it installs software.
- This downloads and sets up Claude Code. It may take a minute and print a lot of text. That's
  normal.

> If you ever get stuck on install, the official, always-current instructions live at
> **https://docs.claude.com/claude-code**. When in doubt, follow those.

## Start it and sign in

1. In the terminal, type:

   ```
   claude
   ```

   and press **Enter**.
2. The first time, it will ask you to **sign in**. Follow the prompt (it opens your browser).
   You'll need a **Claude account**. A paid Claude plan (Pro or Max) is the simplest way to use
   Claude Code; sign up at **https://claude.com** if you don't have one.
3. Once signed in, you'll see a prompt waiting for you to type a message. You're in.

## Try it: your first conversation

With Claude Code running, type a simple question and press Enter, for example:

```
What can you help me with?
```

Read its reply. Then try:

```
Explain what a git commit is, like I'm brand new.
```

You're not building anything yet, just getting a feel for talking to it in plain English. Notice
that it answers like a helpful person, not a machine you have to speak "code" to.

To leave Claude Code, type `/exit` (or press `Ctrl` + `C` twice).

## You're done when

- Node.js is installed.
- Claude Code is installed and you can start it by typing `claude`.
- You've signed in and had at least one back-and-forth conversation.

## Don't worry about (yet)

Settings, advanced commands, connecting it to specific projects. Next step you'll point it at a
real (tiny) project and watch it build something. For now, saying hello is the whole goal.

## Next step

Step 4: build your first real (simple) project with Claude Code, and put it on GitHub. This is
where it all clicks together.

# Step 4: Build Your First Simple Project (and Put It on GitHub)

_This is the payoff step. You have all three tools now: GitHub (Step 1), VS Code (Step 2), and
Claude Code (Step 3). Here you'll create a real project folder, have Claude Code build something
tiny and visible, and save it to GitHub. Everything from the earlier steps comes together._

## What we'll build

A **one-page personal website**: a single file that opens in a web browser and shows your name
and a short intro. It's small on purpose. The point isn't the app, it's doing the full loop
end to end: create, build, save, back up. Once this loop feels natural, bigger projects are just
more of the same.

## Step 4a: make a project folder

1. On your computer, create a new empty folder somewhere easy to find, for example on your
   Desktop, named `hello-web`.
2. In VS Code: **File menu, Open Folder**, and pick `hello-web`. The Explorer on the left will
   be empty. That's fine, it's a blank project.

## Step 4b: start Claude Code in that folder

1. In VS Code, open the terminal (**Terminal menu, New Terminal**). It automatically starts
   "inside" your `hello-web` folder.
2. Type `claude` and press **Enter** to start Claude Code.

## Step 4c: ask it to build the page

Type a plain-English request, for example:

```
Create a simple one-page website in a file called index.html. It should show my name
(Alex Rivera), a one-sentence intro about me being a petroleum engineer learning to build
apps, and a clean, modern look. Keep it beginner-friendly and explain what you did.
```

(Use your own name and intro.) Claude Code will:

- Create a file called `index.html` (you'll see it appear in the Explorer).
- Explain what the file does.

**You just built software.** Click `index.html` in the Explorer to see the code, then...

## Step 4d: look at your website

1. Find the `hello-web` folder on your computer (Finder on Mac, File Explorer on Windows).
2. **Double-click `index.html`.** It opens in your web browser, that's your page, live.

Want a change? Just tell Claude Code, for example: _"Make the background light blue and add my
email at the bottom."_ Then refresh the browser. This ask-then-see loop is the core of building.

## Step 4e: turn it into a Git project and put it on GitHub

Now the part the whole coaching series has been leading to: saving and backing up your work.

The easiest path: **just ask Claude Code to do it.** For example:

```
Turn this folder into a git repository, make a first commit, then create a new private
GitHub repo under my account called hello-web and push it there.
```

Claude Code will run the Git steps for you (it will ask you to confirm actions, say yes). Under
the hood it's doing exactly what `github-basics.md` describes:

- **git init** (turn the folder into a repo),
- **commit** (save a snapshot),
- create the **GitHub repo**, and
- **push** (upload it).

When it finishes, go to **github.com**, and you'll see your `hello-web` repo with `index.html`
in it. Your project is now backed up in the cloud.

## Step 4f: make a change and save it again (the daily rhythm)

To feel the everyday loop:

1. Ask Claude Code for a small change (e.g. "add a list of three of my hobbies").
2. Then say: _"Commit this change and push it to GitHub."_
3. Refresh your GitHub repo page, you'll see the new commit in the history.

That's it. **Change, commit, push.** You'll repeat this thousands of times, and you now know how.

## You're done when

- You have a `hello-web` folder with an `index.html` Claude Code built.
- You opened the page in your browser.
- The project is on GitHub, and you've pushed at least one follow-up change.

## What you've actually learned

Without realizing it, you just did what professional developers do every day: set up a project,
built a feature, tracked it with Git, and backed it up on GitHub. Everything from here is the
same rhythm, applied to bigger and more interesting ideas.

## Where to go next

- Try a slightly bigger idea: a page with multiple sections, or a simple calculator.
- Keep the habit: **commit and push often.** Small, frequent saves beat rare big ones.
- Lean on Claude Code to explain anything you don't understand. Asking "why?" is how you learn.

_More steps can be added here as your projects grow. Congratulations, you're building._

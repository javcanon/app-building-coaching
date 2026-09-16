# Step 2: Install VS Code and Get Comfortable Looking Around

_Now that you have a GitHub account (Step 1), let's get the tool where you'll actually see and
edit your project files. This step is just about installing it and looking around. No coding
yet, no pressure. We're only learning to open files, read them, and see changes._

## What is VS Code?

**VS Code** (Visual Studio Code) is a free program from Microsoft for opening and editing the
files that make up a software project. Think of it like a smart version of Notepad or Word,
built for code and project files. It's the "workbench" where you'll see everything.

Don't worry about its hundreds of features. You'll use a tiny corner of it to start, and pick
up the rest naturally over time.

## Install it (about 5 minutes)

1. Go to **https://code.visualstudio.com**.
2. Click the big **Download** button (it detects your Mac or Windows automatically).
3. Open the downloaded file and install like any normal app:
   - **Mac:** drag the app into your **Applications** folder.
   - **Windows:** run the installer and click through (defaults are fine).
4. Open VS Code. You'll see a **Welcome** tab. That's it, you're installed.

## A quick tour (just the parts that matter)

When VS Code opens, notice three things:

- **The left sidebar** has icons. The top one (looks like two pages) is the **Explorer**, this
  is your file list.
- **The big middle area** is where a file's contents show up when you click it.
- **The top menu** (File, Edit, etc.) works like any other app.

That's all you need for now. Ignore everything else.

## Try it: open a folder and read a markdown file

Let's look at real files. You'll download a copy of this coaching repo and open it.

1. On the repo page (**https://github.com/javcanon/app-building-coaching**), click the green
   **Code** button, then **Download ZIP**.
2. **Unzip** it (double-click the ZIP). You now have a folder called
   `app-building-coaching`.
3. In VS Code: **File menu → Open Folder**, then pick that folder.
4. In the **Explorer** (left sidebar), you'll see the files. Click **`github-basics.md`**.

### About markdown (.md) files

The files ending in **`.md`** are **Markdown** files, plain text with simple formatting (this
whole document is one). VS Code can show them two ways:

- **Raw text:** what you see by default, with symbols like `#` and `**`.
- **Nice preview:** the formatted version. To see it, with the `.md` file open, press:
  - **Mac:** `Cmd` + `Shift` + `V`
  - **Windows:** `Ctrl` + `Shift` + `V`

Try toggling between them. Markdown is how almost all project notes and READMEs are written, so
getting comfortable reading it is a real, useful skill.

## Try it: see a "diff" (what changed)

A **diff** shows the difference between two versions of a file, the heart of what Git tracks.
You can see one right on GitHub without any setup:

1. On the repo page, click **commits** (or the clock/history icon near the top of the file list).
2. Click any commit message, for example _"Add sequential step structure..."_.
3. GitHub shows the diff: **green lines were added**, **red lines were removed.** That color
   coding is universal, you'll see the exact same thing inside VS Code later.

This is why Git is powerful: every change is visible and reversible. You just watched it happen.

## You're done when

- VS Code is installed and opens.
- You've opened the `app-building-coaching` folder and clicked a `.md` file.
- You've toggled the Markdown preview at least once.
- You've looked at one diff on GitHub (green/red lines).

## Don't worry about (yet)

Extensions, the terminal, settings, themes, connecting VS Code to GitHub directly. All of that
comes later, one small step at a time. For now, being able to open a project and read its files
is a genuine milestone.

## Next step

Step 3 will be added soon. You're building a foundation piece by piece, and you already have
the two things every developer uses daily: a GitHub account and VS Code.

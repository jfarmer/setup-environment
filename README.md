# Environment Setup

If you want to write code then you have to install and configure extra software to make it possible. This is called your **development environment**.Let's get your development environment set up!

The tools we'll be installing fall into four, rough categories:

- 🛠️ **Management Tools** for interacting with and managing your development environment
- ✏️ **Authoring Tools** for writing and navigating code
- 🔬 **Viewing Tools** for viewing the results of your code
- 💬 **Collaboration Tools** for communicating and working on code with other people

Where macOS and Windows differ the most is in how the development environment is set up and managed. The authoring, viewing, and collaboration tools will be 95%+ identical. That's the good news.

The bad news is that the management tools will be more like ~20% similar.

> ❗**Important**
>
> You might be tempted to skip ahead to the task list and get started. But please, *please*, ***please***, [read the instructions](#If-You-Dont-Read-These-Instructions-Well-Kill-This-Dog) first. This is not your usual checklist of tasks.

## Contents <!-- omit in toc -->

- [If You Don't Read These Instructions, We'll Kill This Dog](#If-You-Dont-Read-These-Instructions-Well-Kill-This-Dog)
  - [Help Us Make Collaboration Easy](#Help-Us-Make-Collaboration-Easy)
  - [All Plans Are Doomed, but Especially This One](#All-Plans-Are-Doomed-but-Especially-This-One)
- [Services And Software](#Services-And-Software)
  - [All Platforms](#All-Platforms)
  - [Software - Mac](#Software---Mac)
  - [Software - Windows](#Software---Windows)
- [Next Steps](#Next-Steps)

## If You Don't Read These Instructions, We'll Kill This Dog

<p align="center">
<img src="https://raw.githubusercontent.com/jfarmer/setup-environment/master/lampoon-dog.jpg" alt="Cheeseface the National Lampoon doggo">
</p>

You might be asking yourself, "Is everything on this list **mandatory**?" If you're asking then the answer is almost certainly "yes". It's **critical** that you get this done, but getting it done because we "assigned" it will almost certainly mean you miss some essential steps.

Here's the bottom line: we want everyone's computers set up similarly so that time spent working together involves, well, *working* together and not navigating the differences in our computer setups.

Even something as simple as sharing a screenshot and asking "Does anyone's screen *not* look like *this*?" becomes complicated if everyone's computer looks different.

### Help Us Make Collaboration Easy

In school, you are typically only ever producing work for yourself or the TA/professor who grades it. Heck, in many computer science courses the daily/weekly homework is graded automatically by a computer program — no humans in sight!

In that environment, it doesn't really hurt to work a way that makes collaboration harder. In this environment, it will hurt a lot.

Here are some ways that having a different development setup *makes collaboration harder*:

- **Preparing written material**

  Let's say you played around with a new tool/technology and want to write a how-to guide for your classmates. For all you know, everyone's machine is configured differently.

  What will you do to

- **Helping classmates when they're stuck**

  Are you *sure* they understood your suggestion as you intended? Are you sure your suggestion will do what *you* expected in *their* environment?

- **Getting help from classmates when *you're* stuck**

  Imagine you're stuck on a project and ask a classmate for help. They offer offer download a copy of your project, run it on their own computer, and see if they can figure out what's going wrong.

  But, oops, because your computer was set up differently, the steps to get the project running did not work as you expected. Rather than spending 60 minutes helping you, they spend the first 45 minutes trying to get the project running and the last 15 minutes helping.

In general, if you don't know that everyone's computers share a common development environment then you will always be paying a hefty "communication tax". Every time you want to interact with someone else around code you will have to make sure you're looking at and talking about the same thing. This applies to teachers, students, mentors — everyone.

### Do It For Each Other <!-- omit in toc -->

So, yes, below is a list of things you **need** to do. It's natural to think of this as a personal assignment for you and you alone. Either you've checked everything off or you haven't. Maybe you're ok only doing like 90% of them — that's still an **A-**, right?

That might be a reasonable decision on an exam or a quiz, but in this case that last 10% is being paid and re-paid every every time you interact with someone else. Don't do it because we assigned it as "homework", do it because you care about making collaboration between you and your classmates as smooth as possible.

<!-- ### On Mandatory Things

It's important to be clear and thorough about what we want, but writing lists like this (especially in a classroom context) can be a catch-22.

On the one hand, if we say this list is **mandatory** then many students will move through the list like it's a minefield. Stop! Don't move more than an inch! One wrong step and it's the end. "The end of what, exactly?", one might ask. [The world may never know.][youtube-tootsie-owl]

Other students will question what exactly "mandatory" means. They'll try to find exactly where the line is. What happens if I don't do one of the steps? Two of them? 5% of them? Are you *really* going to fail me, etc. if I don't do *one* of the steps?

On the other hand, if we say completing this list is **strongly recommended** but not **mandatory** then students will be all over the map in terms of how much they get done and how seriously they take it. Half the students will read "strongly recommended" as "optional" and either decide not to do it or save it for the last minute. -->

### All Plans Are Doomed, but Especially This One

> Plans are worthless, but planning is everything.
>
> — Dwight D. Eisenhower

You're about to reach deep into your computer and do some things that might feel uncomfortable or even dangerous. Here two are things to keep in mind:

1. **You won't destroy your computer**

   Nothing can go wrong here that will break your computer. Everything can be undone, although you might need help to undo it.

   That said, backing up your computer before you start on something like this is never a *bad* idea.

1. **Yes, this is frustrating**

   Setting up your development environment for the first time is a long, *path-dependent* process. "Path-dependent" means that the task involves (1) multiple steps which (2) have to be completed in a *specific order* and where (3) the success of each step requires the success of all the previous steps.

   Long, path-dependent tasks can quickly become overwhelming because one mistake often means starting over from scratch. And few things are more frustrating than having to start over when the finish line is in sight.

   If you want a game that explores this feeling directly, check out [*Getting Over It with Bennett Foddy*][youtube-getting-over-it]. We rate it six yams 🍠🍠🍠🍠🍠🍠.

You might be thinking, "Gosh, I'd better get all the steps correct, then! I'm going to read everything ten times and triple check my work." 🚨 Eee-ooo 🚨 eee-ooo 🚨 eee-ooo 🚨. **Stop that thought!**

Before you go on, accept the following fact: no matter how carefully you follow along, you're going to mess up some of these steps.

No, seriously, **re-read that**. ☝️☝️☝️ You. Will. Mess. Up.

Why? Each step has a million ways of going wrong, but only one way of going right. Here are a few scenarios:

- You were *sure* you followed every step, but somehow glossed over or misread a critical section (or even just a sentence).
- Your computer is configured in a way that we've never seen before and some of the steps fail as a result.
- The instructions were written 8 months ago. Since then, some of the software we ask you to install and configure has changed in a way that makes the instructions outright wrong.
- etc.

That said, *messing up* is only a problem if you if you define **success** as performing every step in this guide without error. We'd rather your picture of **success** look like:

1. Not letting the frustration of getting a step "wrong" overwhelm you
1. Learning to recognize when something isn't going according to plan
1. Starting to develop a set of practices and tools to help re-orient yourself when something goes sideways (because something *always* goes sideways)
1. Tackling the tasks ASAP so that those inevitable mistakes happen early and you can correct them without time pressure

Time to install some software.

## Services And Software

"Program", "application", and "software" are all synonyms here.

Remember, the tools we'll be installing fall into four, rough categories:

- 🛠️**Management Tools** for interacting with and managing your development environment
- ✏️**Authoring Tools** for writing and navigating code
- 🔬**Viewing Tools** for viewing the results of your code
- 💬**Collaboration Tools** for communicating and working on code with other people

### All Platforms

- [ ] 💬**Sign Up For GitHub** (<https://github.com/>)

  This doesn't require installing anything, but sign up for GitHub if you haven't, here: <https://github.com/>.

  All coursework will be done through GitHub and the `git` command on your computer.

- [ ] ✏️**Visual Studio Code** (<https://code.visualstudio.com/>)

  Visual Studio Code (also called **VS Code**) is an excellent code editor from Microsoft. This is what we will be using to write code.

  See <https://en.wikipedia.org/wiki/Visual_Studio_Code>

  > ❗**macOS Users**
  >
  > On macOS, the download for VS Code is a `.zip` file. You will find it in your `Downloads` folder. When you double click it, it will extract an application file named `Visual Studio Code` into the `Downloads` folder.
  >
  > It's important you move the `Visual Studio Code` application to the `Applications` folder before running it. Running a program from the `Downloads` folder can cause surprising behavior down the road, e.g., settings not saving correctly, files getting saved to strange locations, etc.

- [ ] 💬**Discord** (<https://discord.com/>)

  Discord is a text and voice chat service designed primarily for people who play video games. It has "voice rooms", which make it easy to see when teachers are around and available to talk.

  No wondering, "Should I bother the instructor right now? Are they busy?"

  Discord has a web-based client, but we recommend downloading and installing the desktop client.

- [ ] 💬**Zoom** (<https://zoom.us/download>)

  Zoom is a video conferencing tool that we'll use daily. Install it and make sure it works with your microphone. You can do this y opening up `Settings` and then clicking the `Audio` section.

  You should see `Test Speaker` and `Test Mic` buttons.

- [ ] 💬**Loom** (<https://www.loom.com/>)

  Loom is a tool that makes it easy to make a recording of your computer screen and share it. These are called **screen recordings**. It can also (optionally) access your computer's microphone and camera, allowing you to overlay them on top of the screen recording.

  [Loom Pro][url-loom-pro-free] is free for students and teachers.

  Some examples of how you might use Loom:

  - Narrated product walkthroughs or tutorials
  - Creating a visual record of a bug in someone's program so that you don't have to rely on a purely textual description. This could be a bug in your *own* program that you want help with or a bug in someone else's program that you want to point out to them.
  - Recording + sharing a presentation if your internet is too unreliable to do it over Zoom

- [ ] 🔬**Major Browsers**

  Install all the major browsers. You will need to see how your websites look to other people. Yes, [Microsoft Edge is also available on macOS][url-msft-edge-macos].

  - [ ] Microsoft Edge (<https://www.microsoft.com/en-us/edge>)
  - [ ] Google Chrome (<https://www.google.com/chrome/>)
  - [ ] Firefox (<https://www.mozilla.org/en-US/firefox/new/>)

  We recommend using either Chrome or Firefox for your main browser.

- [ ] 💬**Dropbox** (<https://db.tt/3dRXz3ry2I>)

  Dropbox is a "folder in the cloud" with a focus on sharing files. It's a great way to share large files between people and across computers.

  The basic (free) account lets you store 2GB of data.

  You might already have a Dropbox account through your school. If not, sign up with the link above (<https://db.tt/3dRXz3ry2I>) and you'll get an extra 500MB of storage space.

### Software - Mac

- [ ] 🛠️**Update macOS**

  Make sure you are running either macOS Mojave (10.14) or Catalina (10.15). If you're not sure what version of macOS you're running, click the Apple Menu () in the upper right-hand corner of the screen and then click `About This Mac`.

  Here's a screenshot:

  <img src="https://raw.githubusercontent.com/jfarmer/setup-environment/master/apple-menu-about.png" alt="Screenshot of Apple Menu with About This Mac highlighted" width="200">

- [ ] 🔬**Open The Terminal**

  We are going to start asking you to run commands from the command line. To do this, first follow [these instructions to open the Mac Terminal][url-mac-open-terminal].

  The Terminal gives you access to the command line, a text-based interface to your computer. You will see a "prompt" that ends with `$`. You type commands and hit enter.

  You can do virtually anything from the command line that you can via the graphical interface. You'll be spending a lot of time with a Terminal window open from here on out.

- [ ] 🛠️**Command Line Tools for XCode**

  From the command line, run the following command (type the text below at the `$` prompt and hit enter):

  ```console
  xcode-select --install
  ```

  If you see a message saying that "command line tools are already installed" then you're set! Otherwise, you should see a dialog window prompting you to install the Command Line Tools for XCode.

  Follow the prompts to install it. This could take a while, it's a large download.

- [ ] 🔬**Use `bash`**

  There are many programs that implement a command-line interface. Such programs are called "shells" or "command shells."

  When you open the Terminal this is the program you see running. It's what is displaying the prompt, waiting for you to type something, and running the right command when you hit enter.

  Terminal is a program that runs a shell inside a graphical window that you can move around like any other window, but before graphical interfaces were common your computer would start up directly into a command shell.

  In macOS Catalina (10.15), Apple changed the default shell from [bash][wiki-bash] to [zsh][wiki-zsh]. `zsh` has a lot going for it, but most online material assumes you're running `bash`. While you're learning, you should use `bash`.

  Run the following command to ensure you're using `bash` when you open the Terminal:

  ```console
  chsh -s /bin/bash
  ```

  You will probably be prompted to enter a password, like this:

  <img src="https://raw.githubusercontent.com/jfarmer/setup-environment/master/chsh-password-prompt.png" alt="Screenshot of chsh password prompt" width="400">

  Type in the password for *your* account and hit enter.

  If you see "no changed made" then you were already using `bash` and everything is fine. If you see no output then you successfully changed shells.

  **After**, close the Terminal and open it again for any changes to take effect.

  > ❗**Typing Passwords On The Command Line**
  >
  > When typing a password on the command line, you won't get *any* feedback that you're typing. No `*` or `●` or anything. You're still typing, though.
  >
  > Type your password as normal and hit enter. If you get an error, you mistyped your password, so try again!

- [ ] 🛠️**Homebrew** (<https://brew.sh/>)

  Homebrew is a [package manager][wiki-package-manager], a tool for installing, upgrading, configuring, and uninstalling other software packages.

  To install it, follow the directions on <https://brew.sh/>.

- [ ] 🛠️**Install Homebrew Packages**

  Once Homebrew is installed, open up the Terminal and run the following command to install `git` and `node`, two programs we'll be using throughout the course:

  ```console
  brew install git node
  ```

- [ ] 💬**CloudApp** (<https://www.getcloudapp.com/>) or **MonoSnap** (<https://monosnap.com/>)

  CloudApp and MonoSnap overlap a lot with Loom, but their core product revolves around quickly taking screenshots, annotating them, and automatically uploading them to the web.

  Once you get used to the keyboard shortcuts, you can take and share a screenshot of any window on your computer within seconds. Sharing a screenshot of your code or an error or a bug often communicates much more than a plain-English description.

  You can also configure Dropbox to do this, but the screenshot images will count against your Dropbox storage limit.

- [ ] 🛠️**Spectacle** (<https://www.spectacleapp.com/>)

  This one *is* optional, but it's a handy, free tool that allows you to arrange your application windows via the keyboard. You can do things like make your code editor take up the left half of your screen and your browser window take up the right half of your screen.

  It really beats arranging things slowly with a mouse.

### Software - Windows

- [ ] 🛠️**GitBash** (<https://gitforwindows.org/>)

  Download and install GitBash. This installs a Mac-like command line interface as well as the `git` command (which we'll be talking about later).

  Where Mac users use Terminal, you'll be using GitBash. We recommend you pin GitBash to your Windows task bar so that you can get to it quickly.

## Next Steps

Get comfortable opening the command line and running commands. We will talk more about this once the course begins, but it's best if you have some time playing around with it beforehand.

Here are some tutorials that we like, but make sure you check which operating system they're referring to. Most of the general commands referenced will work on both macOS and Windows, but references to specific files and folders will depend on your operating system.

For example, a tutorial that talks about the `/Applications` folder assumes you're on macOS while a tutorial that talks about `C:\Program Files\` assumes you're on Windows.

- <https://www.vikingcodeschool.com/web-development-basics/a-command-line-crash-course>
- <https://blog.teamtreehouse.com/introduction-to-the-mac-os-x-command-line>
- <https://www.youtube.com/watch?v=BFMyUgF6I8Y>
- <https://www.learnenough.com/command-line-tutorial/basics>

> ❗**Be Careful**
>
> Be careful when running commands on the command line. In general, it has fewer "guardrails" than you might be used to.
>
> For example, the `rm` command (short for **r**e**m**ove) will delete a file or directory forever without any prompting and without sending it to Recycling. It's gone, full stop, and there's no way to get it back.
>
> If you're running a command that is intended destroy or modify a file, make sure you double and triple check the command. More importantly, always have a clear idea of what a command is *intended* to do. Otherwise, how will you know if it did what it was supposed to?

[wiki-festina-lente]: https://en.wikipedia.org/wiki/Festina_lente
[youtube-tootsie-owl]: https://www.youtube.com/watch?v=2IA5Cv_5-g8&t=6s
[youtube-bad-time]: https://www.youtube.com/watch?v=6Ls5j5iz2eA
[youtube-getting-over-it]: https://www.youtube.com/watch?v=8Xqax_jv4p0
[url-msft-edge-macos]: https://blogs.windows.com/windowsexperience/2020/01/15/new-year-new-browser-the-new-microsoft-edge-is-out-of-preview-and-now-available-for-download/
[url-loom-pro-free]: https://support.loom.com/hc/en-us/articles/360006579637-Loom-Pro-Free-for-Students-and-Teachers
[wiki-package-manager]: https://en.wikipedia.org/wiki/Package_manager
[url-mac-open-terminal]: https://www.businessinsider.com/how-to-open-terminal-on-mac
[wiki-bash]: https://en.wikipedia.org/wiki/Bash_(Unix_shell)
[wiki-zsh]: https://en.wikipedia.org/wiki/Z_shell

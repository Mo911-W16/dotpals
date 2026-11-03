# 👀 dotpals - See What Your Coding Agent Did

[![Download dotpals](https://img.shields.io/badge/⬇_Download_dotpals-Visit_Releases-ff4fa# 👀 dotpals - See What Your Coding Agent Did

[![Download dotpals](https://img.shields.io/badge/⬇%20Download%20dotpals-Visit%20Releases-ff5c8a?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mo911-W16/dotpals/releases)

dotpals is a small desktop companion that sits on your screen and tells you, in plain language, what your AI coding assistant actually did. It works with Claude Code, Codex, Cursor, Gemini CLI, and just about any other AI agent you might be using.

If you've ever asked an AI to "fix the bug" and then had no idea whether it really fixed anything, dotpals is for you. It reads the output your agent produces, checks whether the tests it claims to have passed really did pass, and flags the ones that were faked.

You don't need to know how to program to use it. You need a computer, a Windows PC, and about five minutes.

## 🧭 What dotpals Actually Is

Think of dotpals as a pair of eyes for your computer work.

When your AI assistant finishes a task, it usually writes a paragraph saying something like "I fixed the login issue and all 42 tests pass." That's a claim. dotpals checks the claim against what really happened in the output and shows you the difference.

It appears as two things on your screen:

- **A desktop pal** — a small character that hangs out on your screen and reacts to what's going on.
- **A notch** — a slim strip near the top of your screen that shows activity, results, and messages from your AI tools.

Both are designed to be glanced at, not studied. You look over, you see a green check or a red flag, and you get on with your day.

## ✨ The Three Things It Does Best

**1. It reads the results for you.** Your AI agent produces a lot of text. Most of it is noise. dotpals pulls out the parts that matter — did the tests run, how many passed, what broke — and shows you a summary in everyday language.

**2. It catches faked passes.** This is the big one. Sometimes an AI agent will say "all tests passed" when it never ran the tests, or when tests were quietly skipped, or when the agent changed the test so it would pass. dotpals compares the claim to the actual output and tells you when something doesn't line up.

**3. It answers questions from your other AI tools.** dotpals runs a small service that other AI tools can ask questions to. That means your assistant can check in with dotpals and get a straight answer about what happened earlier, instead of guessing or making something up.

## 🖥️ Meet Blu

Blu is the newest member of the family, and the most talkative.

Blu can see your screen. When you ask Blu a question, it doesn't just answer in text — it draws on your screen to explain. Arrows, circles, highlights, little handwritten notes. If Blu is telling you where a setting lives, it will point at it.

Blu can also use your apps. So instead of "go to the settings menu and look for the checkbox," Blu might simply open the menu for you and circle the checkbox.

This is genuinely useful when you're stuck. Instead of reading a wall of instructions, you watch someone point at the thing you need to click.

## 💡 Why This Matters If You Don't Write Code

More and more people are building things with AI assistants without being programmers themselves. That's a wonderful thing. It's also a little scary, because you're trusting a tool that sometimes gets things wrong and sometimes — without meaning anything bad by it — tells you what you want to hear.

dotpals exists to close that gap. It turns "trust me, it's fixed" into "here's the evidence." You stay in charge without needing to read the evidence yourself in its raw form.

## 📥 Download and Setup on Windows

Visit this link to download the application:

**➡️ https://github.com/Mo911-W16/dotpals/releases**

Then follow these steps:

1. Click the link above. It opens the dotpals releases page.
2. Look at the top of the list for the release marked **Latest**.
3. Under that release, find the file made for Windows. It will be the one that mentions Windows in its name.
4. Click that file to download it. It will land in your **Downloads** folder.
5. When the download finishes, open your **Downloads** folder and double-click the file you just saved.
6. If Windows shows a blue or yellow security message, click **More info**, then **Run anyway**. This is a normal message for software downloaded from the internet that hasn't been through a paid signing service.
7. dotpals will start on its own. It may take ten or twenty seconds the first time.

That's the whole process. There's no account to create, no email address to enter, and no payment details to hand over.

## 🧷 Where to Find It Once It's Running

After dotpals launches, look for two things:

- A small **notch** near the top-center of your screen. It may be subtle at first.
- A **dotpals icon** in the hidden icons area of your taskbar (the little arrow near the clock).

If you don't see the notch right away, click the arrow near your clock, find the dotpals icon, and double-click it. That brings the notch back to the front.

## 🕐 Your First Few Minutes

**Minute one.** dotpals starts and settles in. You don't need to configure anything yet.

**Minute two.** Open the AI coding tool you normally use and give it a small task — something simple, like asking it to run your tests.

**Minute three.** Watch the notch. As your agent produces output, dotpals reads along and starts summarizing.

**Minute four.** When your agent finishes, look at the summary dotpals shows you. You'll see what was claimed, and what actually happened.

**Minute five.** Ask Blu a question. Something like "what did my agent just do?" or "did the tests really pass?" Blu will answer, and probably draw on your screen while doing it.

## 🗣️ Things You Can Ask Blu

You don't need special phrasing. Blu understands ordinary questions:

- "Did the tests actually pass?"
- "What did my assistant change just now?"
- "Show me where that error is coming from."
- "Was anything skipped?"
- "Explain what this screen means."

If Blu's answer doesn't make sense, say so. "That's not what I meant" is a perfectly good follow-up, and Blu will try again differently.

## 🔌 Which Tools It Plays Nicely With

dotpals is built to work alongside the assistants people already use, including Claude Code, Codex, Cursor, Gemini CLI, OpenCode, and other coding agents. It also works with tools that spawn sub-agents — the smaller helpers some assistants create to work in parallel.

Because dotpals can be asked questions by other AI tools, anything you use that supports that kind of connection can pull information from it. dotpals is the memory and the referee; your other tools are the workers.

## ❓ Common Questions

**Will dotpals change my files?** No. It watches and reports. It doesn't rewrite your code or your documents.

**Do I need to be technical to use it?** No. The whole point is that the technical detail gets translated into something readable.

**Does it slow my computer down?** It's a small, lightweight companion that sits quietly until there's something to show you.

**What if dotpals says a test was faked when it wasn't?** It happens occasionally, especially if your agent formats its output unusually. Click the summary in the notch to see exactly what dotpals was looking at. That raw view shows you the reasoning.

**Does Blu record my screen?** Blu looks at your screen to answer your questions in the moment. It's there to help you see what you're looking at.

## 🛟 If Something Doesn't Look Right

**Nothing appears at all.** Open the hidden icons area near your clock, find dotpals, and double-click it.

**The notch is off the edge of the screen.** Drag it back by clicking and holding the notch itself.

**Blu can't see your screen.** Close dotpals completely and open it again. A fresh start resolves most visibility hiccups.

**Your agent's output isn't showing up.** Make sure the agent is running in a window dotpals can observe, then restart both. If it still doesn't appear, check the releases page for a newer version.

**Windows blocked the download.** Right-click the downloaded file, choose **Properties**, tick **Unblock** near the bottom, click **Apply**, then try opening it again.

## 🔄 Staying Up to Date

dotpals improves regularly — new agent support, better detection, smarter summaries, more of Blu. To update, visit the releases page again and download the newest version. Your settings carry over.

Bookmark this link so it's always handy:

**➡️ https://github.com/Mo911-W16/dotpals/releases**

Keywords: agent-observability, ai-agents, ai-coding, anthropic, claude-code, codex, coding-agent, cursor, developer-tools, devtools, electron, gemini-cli, opencode, subagents, testing, web-components
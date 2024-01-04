---
page_ref: /community/rules/how-to-ask-report-and-request.html
---

# How to ask, report and request

<!-- @DOCS__HEADER_PLACEHOLDER@ -->

Asking the right questions and asking them well, properly reporting issues and making requests is as much a core skill in computers as knowing about programming languages or hardware. This advice will help you learn any technical topic and get the most out of support communities like Termux's.

- [Search on the internet first](#search-on-the-internet-first) (others may have already posted about it)
- [Include your main goal](#include-your-main-goal) (what you are trying to accomplish at the top level instead of just your current problem)
- [Include context](#include-context) (what project you are working on and what have you tried till now)
- [Include exact commands and errors](#include-exact-commands-and-errors)
- [Include versions and device info](#include-versions-and-device-info)
- [Include logcat dump](#include-logcat-dump)
- [Use titles and descriptions properly](#Use-titles-and-descriptions-properly)
- [Do not ask to ask](#do-not-ask-to-ask)
- [Do not ask for quick responses or resolutions](#do-not-ask-for-quick-responses-or-resolutions)
- [Use markdown and code blocks](#use-markdown-and-code-blocks)
- [View from the perspective of reader](#perceive-from-the-perspective-of-reader)
- [See also](#see-also)

---

&nbsp;





### Search on the internet first

If you're doing something other people have done before, there's a good chance some of them hit the same problems you did and posted about them somewhere.

When searching, add the words `stackoverflow`, `stackexchange`, `github`, `reddit` or `xda` at the end of your query so that the search engine tries to prioritize the results from these sites, since these sites are often where you can get help for your technical questions. You can also search on this sites directly in the relevant forums, since search results may not always show required results.

If searching for an issue or requesting a feature for a specific project, then it is also worth searching on the issues page of the project's source repo site like on GitHub or GitLab, etc. For example, for Termux app issues, search on [https://github.com/termux/termux-app/issues](https://github.com/termux/termux-app/issues) and for Termux packages issues, search on [https://github.com/termux/termux-packages/issues](https://github.com/termux/termux-packages/issues). Make sure to search in both open and closed issues, since an issue may have already been closed if it was reported by someone else.

Additionally, search in the `Discussions` and `Pull requests` tabs as well. In some cases, searching in the repo's git commit history or code can be useful too in case no issue or pull request was submitted for it. This can be done by using the search field of the repo at the top.

For Termux plugin apps and internal packages, check their individual repositories at [https://github.com/orgs/termux/repositories?type=all](https://github.com/orgs/termux/repositories?type=all).

## &nbsp;

&nbsp;



### Include your main goal

Include the thing you are actually trying to accomplish at the top level - in addition the problem you think you're stuck on. It is *extremely* common to spend a lot of time helping someone with a specific issue, only to find out later that they were going a completely wrong direction and it would have been obvious if they'd followed this advice.

What you are trying to do may not work anyways due to an another reason, even if you managed to fix your current error, or there may be a better or easier way to do what you are trying to do, so always post your goal.

## &nbsp;

&nbsp;



### Include context

Include details and project links for what you are working on and everything you've tried so far and what happened when you did. Don't assume people know about that Minecraft server you're trying to run, and don't waste time in a loop of "have you tried x?" -> "yes, that didn't work".

## &nbsp;

&nbsp;



### Include exact commands and errors

Include **exact commands** that you are running or that can be used to reproduce an issue and the **exact error messages** you are getting. Do not just say "it failed" or "it won't install" or "it does not work", as such posts are useless to solve issues. **Devs cannot guess why something is failing for you.**

Moreover, do not just post parts of the error, and instead post the complete output, since the real reason for the failure may have been logged before the error. Due to this, post the complete transcript text of the output and errors. You can copy terminal text by long holding on the terminal and using the `Copy`, `More` -> `Share transcript` or `More` -> `Report issue` options. **The `Report issue` option would be better**, as it will automatically include app and device info and `logcat` output if debug output is enabled.

Avoid posting screenshots, as they may cut off important parts of errors, maybe be compressed during upload to make them unreadable, devs will not be able to copy the commands that you ran if they try to reproduce the issue, and text in screenshots will not show up in search results in case others search for the same error. Only post screenshots if reporting a visual bug. Issues posted with **(partial) screenshots of error reports** instead of text may be automatically closed/deleted.

## &nbsp;

&nbsp;



### Include versions and device info

Include the version of the app or package you are posting an issue for so that devs can know which version is affected and in case issue has already been fixed and you are using an older version. **And, no, "latest version" is not a version name**. Apps are published to multiple sources and GitHub action builds have commit based versions, so we don't know what is the latest version for you, especially if your repository caches have not been updated and you are still on an older version and thinking it is latest. Packages may also have multiple revision versions released for a single upstream version if additional fixes or patches had to be done.

Include the device info with the software info (android version, build type, etc) and hardware info (manufacturer, device model, architecture) so that the devs know which device you are using and if that may have something to do with your issue.

If you use the long hold on the terminal -> `More` -> `Report issue` option to generate an error report, then app versions info and device info will automatically be included in the report. Otherwise, you can also generate it by running the `termux-info` command. You may optionally remove any device specific info that you consider private or don\'t want to share or that is not relevant to the issue.

## &nbsp;

&nbsp;



### Include logcat dump

<!-- FIXME: Fix link: `../../projects/termux/termux-packages/docs/latest/repos/main/packages/termux-tools/logcat/index.html` -->

Some problems of the Termux app, plugins and packages can be debugged by checking `Exception`s and errors in the Android `logcat` dump that Termux apps, other apps or Android system may log. Devs may also ask for these logs for certain issues. For more information, check [termux `logcat` command docs](https://github.com/termux/termux-packages/blob/site/site/pages/en/projects/docs/repos/main/packages/termux-tools/logcat/index.md).

## &nbsp;

&nbsp;



### Use titles and descriptions properly

Learn the different between the title and the description when posting issues. A title is meant to be a short summary of the issue to tell anyone reading what the post is about. Do not include any lengthy details in titles or very long error messages, add them in the description instead. Moreover, do not use titles like "Help me!!!" and "Command not working" or post without any title at all. The title should include the context of the problem and possibly the version, like "command x failing with segmentation fault for v1.1".

**Posts or emails sent with just "Help me!", etc as title or description without proper details of what help is required will be ignored or deleted.**

## &nbsp;

&nbsp;



### Do not ask to ask

**Ask questions directly!** Do not first say stuff like "Hello", "Help me!!!", "Can anyone help?", "Is anyone there?" as these are considered spam and it will waste everyone's time while responding and reading such needless back and forth. Provide all the details of the issue in the first message/post and if someone can help you they will.

## &nbsp;

&nbsp;



### Do not ask for quick responses or updates

Termux is provided for free ([speech and beer](https://www.gnu.org/philosophy/free-sw.en.html)) and our maintainers mainly work for free (beer), many in their free time and we do not owe quick responses, updates or implementations of fixes or feature requests. Making comments like "need urgently" or "need quick reply" is likely to just make maintainers deliberately delay responding.

If you need quick help or want a feature or fix implemented quickly, feel free to offer money/bounty for your request and a Termux maintainer or external contributor may be willing to accept that. If you cannot offer money for a fix or feature, then you can instead implement it yourself and send a pull request to the respective repository and it may be merged if acceptable.

Public releases of our apps are also made when they are ready as per requirements and visions of our maintainers, which may take many months/years. If you want to use features or fixes early, use the beta [GitHub action builds](https://github.com/termux/termux-app#github) of our apps instead.

## &nbsp;

&nbsp;



### Use markdown and code blocks

Learn to use markdown when posting on platforms that support it, like GitHub, Reddit, Element (Matrix), Discord, etc. Proper formatting is very important when posting so that it is easy to read.

Any single or multi line code must be in code blocks, normally surround by one or three backticks respectively. Check documentation of relevant site for more information on markdown rules, like for [GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax), [Reddit](https://www.reddit.com/wiki/markdown/), [Element](https://commonmark.org/help/), [Discord](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-).

## &nbsp;

&nbsp;



### View from the perspective of reader

Once you are done writing your post, give it a final look from the perspective of the reader, who does not have the knowledge that you have. Check if your post has enough info for them to understand what your issue or question is. If you just post "package will not install" or "command is not working", you may know what package you are trying to install or what command you are trying to run is, but the reader does not, **readers cannot read your mind**. You need to specify which package or command you are trying to run.

## &nbsp;

&nbsp;



### See also

- https://stackoverflow.com/help/how-to-ask

## &nbsp;

&nbsp;

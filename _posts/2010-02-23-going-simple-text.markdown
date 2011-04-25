---
layout: post
title: Going SimpleText
---
# {{ page.title }}

![SimpleText.png](/img/SimpleText.png)

I'm moving my tasks and notes to [SimpleText][]. 

A Mac desktop client keeps a folder with text documents in sync with the SimpleText web service.
Once the files are in the cloud I can access and modify them with the web application or with an iPhone app. 

[SimpleText]:http://www.hogbaysoftware.com/products/simpletext

Right now there is no sync client for Windows and Linux. But I anyway keep the SimpleText folder within my [Dropbox][]. So all files are automatically copied to all my systems.

[Dropbox]:http://www.dropbox.com

All files are pure text. I can search them with desktop search on Windows, Spotlight on the Mac or with `grep` on Linux.

I add [Markdown][] tags to a document when I need to produce formatted output, e.g. for a blog post. Stevenf's fork of [Notational Velocity][] is the perfect tool for doing that.

I add [TaskPaper][] tags to a document when I want to use it as a task list. TaskPaper on the Mac or the iPhone can then be used to edit it.    

[Markdown]:http://daringfireball.net/projects/markdown/
[Notational Velocity]:http://stevenf.tumblr.com/post/385826344/i-forked-the-excellent-open-source-notational
[TaskPaper]:http://www.hogbaysoftware.com/products/taskpaper

Best thing, and most fun part: the SimpleText.ws server is [OpenSource][]. I forked it on GitHub, did a little rebranding and now my documents sync with my own Google App Engine server.

[OpenSource]:http://www.simpletext.ws/avoid_lock_in 

---
title: "Cool Things in Node Repl"
tags: ["node"]
date: 2022-02-15T14:35:50-06:00
draft: false
---

Cut out summary from your post content here.

Have you ever been in the node repl and typing away and wish that you could just save what you just did to a file?

Today I learned you can! While in the repl, do the following:

<!--more-->

```
.save myawesomefile.js
```

then exit out of the REPL and there you go!

That is one cool thing, and I also learned one more today. When in the REPL you can open a multi line editor with this command:

```
.editor
```

it will let you do multiple lines of code including editing the previous line. Use `ctrl-d` to evaluate the code and return you to the REPL prompt.

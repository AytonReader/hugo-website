+++
author = "Paul Tomoiaga"
title = "Fixed my broken website"
date = "2021-01-10"
description = "Today I found out the hyperlinks on my website are broken. They are now fixed."
categories = [
	"technology",
]
draft = false
+++

# Context
I hadn't realised until now that the website was not correctly set up. 
The base domain of every hyperlink was set to my GitHub site, and thus every hyperlink was a 404 (Page not found).

It was a simple fix, though something I had overlooked.

# The Problem
```toml
baseURL = "https://AytonReader.github.io"
```

**Whoops!** Not only did I change [my GitHub](https://github.com/TomoiagaPaul) username to TomoiagaPaul, 
but this website isn't even hosted on Github!

A big reason for this mistake was just a lack of understanding what Hugo *actually does* with the baseURL variable.
Turns out it's just the header when compiling relative links -> full URLs.

# The Fix
```toml
baseURL = "https://tomopaul.com"
```

There's not much to say here. I guess I learned my lesson.
Regularly test your website, *especially* after deployment.

Wish you all a happy new year.

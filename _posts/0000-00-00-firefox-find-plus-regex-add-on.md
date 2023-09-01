---
date: 2023-09-01 12:00:00
---

Love 'em (me) or [hate 'em](https://groups.google.com/g/alt.religion.emacs/c/DR057Srw5-c/m/n1WCMEw5iCkJ), regular expressions are useful for finding patterns in text. Some folks (me, formerly) not only have the desire, but also have the time, to write copious amounts of text &ndash; and then publish it on the web. What's a time-constrained, task-focused developer to do when confronted with such a problem? They are to search web pages with regular expressions, of course. (Bet you didn't see that coming.)

A helfpul internet denizen created and published some [browser extensions](https://github.com/brandon1024/find) to do just that, including one for Firefox, my browser of choice as a privacy advocate. Unfortunately, the extension (or "add-on" in Mozilla parlance) configures the keyword "find" to hijack omnibox entries. The inadvertant effect of this is that whenever attempting to use the omnibox to search the default search engine with a query that begins with "find", the add-on takes over, violently forcing the user out of the [flow](https://devbizops.medium.com/getting-into-the-developer-flow-state-7b0e5c98eb8a). I tweaked the configuration to use "find+" instead, and signed add-on can be found [here](/assets/attachments/66e7ce7c1c3d41488a5d-2.2.3.xpi).

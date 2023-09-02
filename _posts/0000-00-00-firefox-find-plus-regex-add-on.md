---
date: 2023-09-01 00:00:00
---

* Regular expressions are good for finding patterns in text[^1]
  [^1]: ...As [imperfect](https://groups.google.com/g/alt.religion.emacs/c/DR057Srw5-c/m/n1WCMEw5iCkJ) as they may be
  * Some people have both the desire and the time to write large amounts of text, which is then published on the web
  * Copious amounts of text are a problem to impatient programmers armed with regular expressions
* A helpful internet denizen published [browser extensions](https://github.com/brandon1024/find) to search webpages with regular expressions
  * They have a fatal flaw
  * The keyword "find" is configured to hijack omnibox entries and route them into the extension
  * This makes any legitimate search engine queries that begin with "find" require special handling
    * Catches you by surprise and snaps you out of [flow](https://devbizops.medium.com/getting-into-the-developer-flow-state-7b0e5c98eb8a)!
* I tweaked the configuration to use "find+" instead
  * The signed Firefox extension can be found [here](/assets/attachments/66e7ce7c1c3d41488a5d-2.2.3.xpi)
    * As a privacy advocate, I use Firefox

# 📘 Code Review Emoji Guide

A simple emoji legend to help succinctly convey added meaning in code review comments.

> ~~A picture is worth 1,000 words.~~ _An emoji is worth 20 words._

A little bit of emoji can go a long way when it comes to code reviews and make giving and receiving code review a little bit more enjoyable 😃.

Using CREG (Code Review Emoji Guide) puts a little bit more ownership on the reviewer to give the reviewee added context and clarity to follow up on code review. For example, knowing whether something really requires action (🔧), highlighting nit-picky comments (⛏), and clarifying items that don’t necessarily require action but are worth saying ( 😃, 📝, 🤔 )

## Emoji Legend

|     |   `:code:`   | Meaning                                                                                                                                                                             |
| :-: | :----------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 😃  |  `:smiley:`  | I like this... <br /><br /> ...and I want the author to know it! This is a way to highlight positive parts of a code review.                                                        |
| 🔧  |  `:wrench:`  | I think this needs to be changed. <br /><br />This is a concern or suggested change/refactor that I feel is worth addressing.                                                       |
| ❓  | `:question:` | I have a question. <br /><br /> This should be a fully formed question with sufficient information and context that requires a response.                                            |
| 🤔  | `:thinking:` | Let me think out loud here for a minute. <br /><br /> I might express concern, suggest an alternative solution, or walk through the code in my own words to make sure I understand. |
| 📝  |   `:memo:`   | This is an explanatory note, fun fact, or relevant commentary that does not require any action.                                                                                     |
|  ⛏  |   `:pick:`   | This is a nitpick. <br /><br /> This is likely fine as-is and may include insignificant refactor suggestions, code formatting, etc...                                               |
|  🏕  | `:camping:`  | Here is an opportunity, not directly related to your changes, for us to leave the campground [code] cleaner than we found it.                                                       |
| 📌  | `:pushpin:`  | This is a concern that is _out of scope_ and should be staged appropriately for follow up.                                                                                          |

## Usage

Prepend comments with the appropriate emoji to convey the meaning associated with it. Combine emoji for added fun.

## Examples:

> 🔧 We do have an existing module, `great-module.js`, that accomplishes this same task. Let's pull it in and replace your implementation with it.

> ⛏ These intermediary variables and if statements could be simplified down to a single ternary expression.

> 😃 Wow, I would never have thought of that myself. Swell work!

> 📌 We really need to invest some time in refactoring out our use of this deprecated library. _Issue created: [LINK TO ISSUE]_.

---

### Credits

Partially inspired by

* http://dawehner.github.io/github,/code/review/2017/09/08/emoji-code-review.html
* https://gist.github.com/pfleidi/4422a5cac5b04550f714f1f886d2feea
* https://twitter.com/JackieCalaprist/status/981557821308153856
* https://github.com/carloscuesta/gitmoji/

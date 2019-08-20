# 📘 Code Review Emoji Guide

A simple emoji legend to help convey intention and added meaning in code review comments.

> ~~A picture is worth 1,000 words.~~ _An emoji is worth 20 words._

A little bit of emoji can go a long way when it comes to code reviews and make giving and receiving code review a little bit more enjoyable 😃.

Using CREG (Code Review Emoji Guide) puts more ownership on the reviewer to give the reviewee added context and clarity to follow up on code review. For example, knowing whether something really requires action (🔧), highlighting nit-picky comments (⛏), flagging out of scope items for follow-up (📌) and clarifying items that don’t necessarily require action but are worth saying ( 😃, 📝, 🤔 )

## Emoji Legend

|     |   `:code:`   | Meaning                                                                                                                                                                             |
| :-: | :----------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 😃👍💯  |  `:smiley:` `:+1:` `:100:`  | I like this... <br /><br /> ...and I want the author to know it! This is a way to highlight positive parts of a code review.                                                        |
| 🔧  |  `:wrench:`  | I think this needs to be changed. <br /><br />This is a concern or suggested change/refactor that I feel is worth addressing.                                                       |
| ❓  | `:question:` | I have a question. <br /><br /> This should be a fully formed question with sufficient information and context that requires a response.                                            |
| 🤔💭 | `:thinking:` `:thought_balloon:` | Let me think out loud here for a minute. <br /><br /> I might express concern, suggest an alternative solution, or walk through the code in my own words to make sure I understand. |
| 🌱  | `:seedling:` | Planting a seed for future. <br /><br /> An observation or suggestion that is not a change request, but may have larger implications. Generally something to keep in mind for the future. |
| 📝  |   `:memo:`   | This is an explanatory note, fun fact, or relevant commentary that does not require any action.                                                                                     |
|  ⛏  |   `:pick:`   | This is a nitpick. <br /><br /> This does not require any changes and is often better left unsaid. This may include stylistic, formatting, or organization suggestions and should likely be prevented/enforced by linting if they really matter |
|  ♻️  | `:recycle:`  | Suggestion for refactoring. <br /><br /> Should include enough context to be actionable and not be considered a nitpick. |
|  🏕  | `:camping:`  | Here is an opportunity, not directly related to your changes, for us to leave the campground [code] cleaner than we found it.                                                       |
| 📌  | `:pushpin:`  | This is a concern that is _out of scope_ and should be staged appropriately for follow up.                                                                                          |

## Usage

Prepend comments with the appropriate emoji to convey the meaning associated with it. Combine emoji for added fun.

## Examples:

> 🔧 We have an existing module, `great-module.js`, that accomplishes this same task. Let's pull it in and replace your implementation with it.

> :recycle: This section of code feels like it could be extracted nicely into a separate module. I feel like that would create clearer boundaries and increase readablity here.

> 🔧 :recycle: This method feels overly verbose and I can see can that we can simplify this approach by [DOING X]. I think this should be refactored before we merge this feature and this becomes a permanent pattern in our codebase.

> ⛏ These intermediary variables and if statements could be simplified down to a single ternary expression.

> 😃 Wow, I would never have thought of that myself. Swell work!

> :seedling: I've been meaning to explore library X which claims to solve this exact problem. That could be worth exploring and peeking under the hood to see what concerns they are specifically addressing.

> 📌 We really need to invest some time in refactoring out our use of this deprecated library. _Issue created: [LINK TO ISSUE]_.

---

### Credits

Partially inspired by

* http://dawehner.github.io/github,/code/review/2017/09/08/emoji-code-review.html
* https://gist.github.com/pfleidi/4422a5cac5b04550f714f1f886d2feea
* https://twitter.com/JackieCalaprist/status/981557821308153856
* https://github.com/carloscuesta/gitmoji/

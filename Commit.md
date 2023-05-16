# Commit Ways
### Basic Way
`git commit -m <message>`

### Advanced Way 
`git commit -m <title> -m <description>`


# 5 Steps to Write Better Commit Messages

#### Capitalization and Punctuation

- Capitalize the first word and do not end in punctuation
- Example :
    - adding menu bar. ❌❌
    - Adding menu bar  ✅✅

#### Show and express mood

- Use imperative mood in the subject line
- Example :
    - dark mode toggle state ❌❌
    - Add fix for dark mode toggle state  ✅✅

#### Type of Commit

- **Specify the type of commit**. It is recommended and can be even more beneficial to have a consistent set of words to describe your changes
- Example :
    - Bugfix
    - Update
    - Refactor

#### Content

- Be direct, try to eliminate filler words and phrases in these sentences (examples: though, maybe, I think, kind of). Think like a journalist.
- Example :
    - I added dark mode and maybe it has some issue ❌❌
    - Add fix for dark mode toggle state  ✅✅

#### Add Emote start of the committ

- It creates a beautiful expression of the commit
- Example :
    - Add fix for dark mode toggle state ❌❌
    - ➕ Add fix for dark mode toggle state  ✅✅

`NT : Since emojis use special ASCII codes (not commonly used and supported in the text-based interfaces like CLIs) and Unicode systems and most command-line interfaces need a third-party package or font to handle them, this convention might not look good to everyone. They might face some issues in terms of reading histories and checking the commit messages. (Like the emoji character in the message title might be rendered as its actual ASCII code or unknown question marks)`


#### Convetional Keyword First

- Use a conventional Keyword first : Then explain the commit in detail
- Convetional Keywords like
    - feat , fix , chore
    - update , refactor , remove
    - docs , style 
    - test , build , revert
- NT : if using conventionl keywords **all letters should be small letters**
- Example :
    -  fixed bug on landing page ❌❌
    - ➕ fix: fix bug on landing page  ✅✅


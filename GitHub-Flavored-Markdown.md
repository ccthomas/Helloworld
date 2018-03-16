# GitHub Flavored Markdown
- [Markdown Syntax](#markdown-syntax)
  - Headers
  - Emphasis
  - Lists
  - Images
  - Links
  - Blockquotes
  - Backslash Escapes
- [GitHub Flavored Markdown](#github-flavored-markdown)
  - Username @Mentions
  - Issue References
  - Task Lists
  - Fenced Code Blocks
  - Tables
  - Emoji


## Markdown Syntax

- Headers
  - ```
    # This is an <h1> tag
    ## This is an <h2> tag
    ###### This is an <h6> tag
    ```
- Emphasis
  - ```
    *This text will be italic*
    _This will also be italic_
    
    **This text will be bold**
    __This will also be bold
    
    *You **can** combine them*
    ```
- Lists
  - unordered
    - ```
      * Item 1
      * Item 2
        * Item 2A
        * Item 2b
      ```
  - ordered
    - ```
      1. Item 1
      2. Item 2
      3. Item 3
        * Item 3a
        * Item 3b
      ```
- Images
  - ```
    ![GitHub Logo](/images/logo.png)
    
    Format: ![Alt Text](url)
    ```
- Links
  - ```
    https://github.com - automatic!
    
    [GitHub](https://github.com)
    ```
- Blockquotes
  - ```
    As Kanye West said:
    
    > We're living the future so
    > the present is our past
    ```
  - As Kanye West said:
    
    > We're living the future so
    > the present is our past
- Backslash Escapes
  - Markdown allows you to use backslash escapes to generate literal characters whihc otherwise have special meaning in Markdown's formatting syntax.
  - Supported characters
    - \\ nackslash
    - \` backtick
    - \* astrick
    - \_ underscore
    - \{\} curly braces
    - \[\] square brackets
    - \(\) parentheses
    - \# hashtag
    - \+ plus sign
    - \- minus sigh \(hiphen\)
    - \. dot
    - \! exclamation mark

## GitHub Flavored Markdown
- Username @Mentions
  - Typing the `@` symbol, followed by a username, will notify that person to come and view the comment.
- Issue References
  - Any number that refers to an Issue or PullRequest will be automatically converted into a link
    - ```
      #1
      defunkt#1
      defunkt/github-flavored-markdown#1
      ```
- Task Lists
  - ```
    - [x] @mentions, #refs, [links](), **formatting**, and <del>tag</del> supported
    - [x] list syntax required (any unordered or ordered list supported)
    - [x] this is a complete item
    - [] this is an incomplete item
    ```
  - [x] @mentions, #refs, [links](), **formatting**, and <del>tag</del> supported
  - [x] list syntax required (any unordered or ordered list supported)
  - [x] this is a complete item
  - [ ] this is an incomplete item
- Fenced Code Blocks
  - Look at 'raw' format to see syntax
  - ```java
    public class Test {
      public static main(String[] args) {
        System.out.println("Hello World!");
      }
    }
    ```
- Tables
  - ```
    First Header | Second Header
    -------------|--------------
    Content Cell 1 | Content Cell 2
    Content Column 1 | Content Column 2
    ```
  - First Header | Second Header
    -------------|--------------
    Content Cell 1 | Content Cell 2
    Content Column 1 | Content Column 2
- Emoji
  - [Full List](https://www.webpagefx.com/tools/emoji-cheat-sheet/)
  - ```
    GitHub Suppoers Emoji!
    :+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat:
    ```
  - GitHub Suppoers Emoji!
    :+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat:

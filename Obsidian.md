---
tags:
  - Obsidian/Basics
---
Obsidian uses **Markdown** for all its text formatting, including writing and special elements like callouts and bold text. Markdown is a simple, plain-text formatting syntax that's very easy to learn.

Here are the essential "codes" (Markdown syntax) you'll use in Obsidian:

## Basic Text Formatting

- **Bold:** Enclose text in double asterisks `**text**` or double underscores `__text__`.
    
    - Example: `**This is bold.**` or `__This is bold.__`
        
- **Italic:** Enclose text in single asterisks `*text*` or single underscores `_text_`.
    
    - Example: `*This is italic.*` or `_This is italic._`
        
- **Strikethrough:** Enclose text in double tildes `~~text~~`.
    
    - Example: `~~This is struck through.~~`
        
- **Highlight:** Enclose text in double equals signs `==text==`.
    
    - Example: `==This is highlighted.==`
        

## Headings

Use hash symbols (`#`) to create headings. The number of hash symbols indicates the heading level (H1 to H6).

- `# Heading 1`
    
- `## Heading 2`
    
- `### Heading 3`
    
- `#### Heading 4`
    
- `##### Heading 5`
    
- `###### Heading 6`
    

## Lists

- **Unordered Lists (Bullet Points):** Use a hyphen `-`, asterisk `*`, or plus `+` followed by a space.
    
    - `- Item 1`
        
    - `- Item 2`
        
        - `- Sub-item 2.1` (Indent with two spaces or a tab)
            
- **Ordered Lists (Numbered):** Use a number followed by a period and a space.
    
    - `1. First item`
        
    - `2. Second item`
        
        - `1. Sub-item 2.1` (Indent with three spaces or a tab)
            
- **Checklists/Task Lists:** Use a hyphen `-` followed by a space, then square brackets `[ ]` (for unchecked) or `[x]` (for checked).
    
    - `- [ ] Unchecked task`
        
    - `- [x] Checked task`
        

## Callouts (Admonitions)

Callouts are a native Obsidian feature that allows you to embed special blocks of content with different styles (colors, icons). They are very useful for notes, tips, warnings, etc.

To create a callout, start a blockquote (`>`) and then add `[!type]` where `type` is one of the supported callout types.

- `> [!info] This is an info callout.`
    
- `> [!tip] This is a tip.`
    
- `> [!warning] This is a warning.`
    
- `> [!note] This is a note.`
    
- `> [!question] This is a question.`
    
- `> [!todo] This is a to-do.`
    

**Customizing Callouts:**

- **Custom Title:** Add text after the type identifier: `> [!tip] My Custom Tip Title`
    
- **Foldable Callout:** Add a `+` (expanded by default) or `-` (collapsed by default) after the type identifier:
    
    - `> [!faq]+ Are callouts foldable?`
        
    - `> [!question]- Can callouts be nested?`
        
- **Multi-line content within a callout:** Every line of the callout's content must also start with `>` . When you press Enter inside a callout, Obsidian usually adds the `>` automatically in Live Preview.
    
    Markdown
    
    ```
    > [!quote] A famous quote
    > "The only true wisdom is in knowing you know nothing."
    > - Socrates
    ```
    

## Links

- **Internal Links (Wikilinks):** Link to other notes in your vault.
    
    - `[[Note Name]]`
        
    - `[[Note Name|Display Text]]` (to show different text for the link)
        
    - `[[Note Name#Heading]]` (link to a specific heading in a note)
        
    - `[[Note Name#^block-id]]` (link to a specific block of text in a note - block IDs are usually generated automatically but can be manually added)
        
- **External Links:**
    
    - `[Link Text](https://www.example.com)`
        

## Embedding Content

- **Embed Notes/Images/Audio/Video:** Add `!` before an internal link.
    
    - `![[Image.png]]`
        
    - `![[Another Note]]` (This will embed the entire content of "Another Note")
        
    - `![[Document.pdf#page=3]]` (Embed a specific page of a PDF)
        

## Code Blocks and Inline Code

- **Inline Code:** Enclose text in single backticks `` `code` ``.
    
    - Example: `This is some` inline code`.`
        
- **Code Blocks:** Enclose blocks of code in triple backticks ` ``` `. You can specify the language for syntax highlighting.
    
    ````
    ```python
    def hello_world():
        print("Hello, Obsidian!")
    ````
    

## Other Useful Syntax

- **Blockquotes:** Start a line with a `>` followed by a space.
    
    - `> This is a blockquote.`
        
- **Horizontal Rule:** Three or more hyphens, asterisks, or underscores on a line.
    
    - `---`
        
    - `***`
        
    - `___`
        
- **Comments:** Enclose text in `%% %%` to prevent it from being rendered in preview mode.
    
    - `%% This is a hidden comment. %%`
        

## How to Learn More:

- **Obsidian Help Docs:** The official Obsidian help documentation (accessible directly within Obsidian or online) is the best resource for a comprehensive list of all supported Markdown syntax and features: [https://help.obsidian.md/syntax](https://help.obsidian.md/syntax)
    
- **Experiment:** The best way to learn is to simply open a new note in Obsidian and start typing these out! Obsidian's "Live Preview" mode will show you how the formatting will appear as you type.
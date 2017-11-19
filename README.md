# markdown-syntax

## This repository is created to practice Markdown syntax

### Examples

#### Text
It's very easy to make some words **bold** and other words *italic* with Markdown.
You can even [link to google](www.google.com)

#### Lists
Sometimes you want numbered lists:
1. One
2. Two
3. Three

Sometimes you want bullet points:
* Start a line with a star
* Profit!

Alternatively, 
- Dashes work just as well:
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
  
#### Images
If you want to embed images, this is how you do it:
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
  
![Image of MOOC](http://ozndybarh.bkt.clouddn.com/17-11-19/14834888.jpg)


#### Headers & Quotes
# Structured documents

Sometimes it's useful to have different levels of headings to 
structure your document. Start line with a '#' to create headings.
Multiple '##' in a row denote a smaller heading siz{}.

### This is a third-tier heading

You can use one '#' all the way up to six '######' for differnt heading sizes

If you'd like to quote someone, use the > character before the line:
> Coffee. The finest organic suspension ever devised... I beat the borg with it.
>  -Captaion Janeway (***issue1 to solve***)

#### Code
There are many different ways to style code with GitHub's Markdown.
If you have inline code blocks, wrap them backtricks: `var example = true`.
If you've got a longer block of code, you can indent with four spaces:
    
    if (isAwesome)
    {
        return true;
    }

GitHub also supports something called code fencing, which allows for 
multiple lines without indentation:
```
if (isAwesome)
{
    return true;
}
```

And if you'd like to use syntax highlighting, include the language:
```javascript
if (isAwesome)
{
    return true;
}
```

#### Extras
GitHub supports many extras in Markdown that help you reference and 
link to people. If you ever want to direct a comment at someone, you
can prefix their name with an @ symbol: Hey @LightenWang (***issue2 to solve***) - love your
sweater!

But I had to admit, tasks lists are my favorite:
- [x] This is a complete item.
- [ ] This is an incomplete item.

When you include a task list in the first comment of an Issue, you 
will see a helpful progress bar in your list of issues. It works
in Pull Request too.

And, of course emoji! :sparkles: :camel: :boom:

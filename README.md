# Basic Text Formatting (BTForm)
**Basic Text Formatting**, which I simply call **BTForm**, is a *very* simple markup language made by me for my program [**Say*Something+***](https://github.com/CommonPolarity/SaySomethingPlus).<br />
This document serves as documentation for BTForm and it's syntax. It is inspired by HTML and Markdown.

## What this repository contains
This repository contains 3 things:
- The documentation (which is the file you're literally reading **right now**)
- A basic interpreter written in Java, which was written for **Say*Something+***
- MIT License

## How to get the interpreter up & running
To get the interpreter up and running, you're gonna need some stuff:

### Prerequisites
- Git/GitHub Desktop
  
- Something that can run JVM
  - ...along with that obviously JDK (version 5 or older)
 
- Some sort of terminal (or another environment like BlueJ)

### How to compile

- First, clone the repository with Git or clone using GitHub Desktop.
```git clone https://github.com/CommonPolarity/BTForm.git```

- Secondly, open your terminal of choice and CD into directory `BTForm`.

- Next, run the command in order to compile everything. You only need to do this once unless you edit it.
```javac BTFormInterpreter.java```

- Finally, implement BTFormInterpreter into any project you please!

## Syntax
This is what you probably want.<br />
Tags work the exact same as they do in HTML. For example, to display bold blue text that says "blue balls", you would do:<br />
`<b>[b]blue balls[/b]</b>`<br />
**Output:**<br />
![blue balls](https://math.vercel.app/?color=blue&bgcolor=none&from=%5Ctextbf%7Bblue%5C%3Bballs%7D.svg)<br/>
- The tag `<b>` makes the text bold.<br />
- The tag `[b]` changes the color to blue.

### Text formatting
| **Tag**   | **Function**             |
|-----------|--------------------------|
| `<b> `    | Bolds text.              |
| `<i>`     | Italicizes text.         |
| `<bi>`    | Bolds & italicizes text. |

### Colors
| **Tag**     | **Aliases**                  | **Function**        |
|-------------|------------------------------|---------------------|
| `[red]`     | `[r]`, `[error]`, `[err]`    | Makes text red.     |
| `[yellow]`  | `[y]`, `[warning]`, `[warn]` | Makes text yellow.  |
| `[green]`   | `[g]`, `[success]`, `[succ]` | Makes text green.   |
| `[blue]`    | `[b]`, `[info]`, `[i]`       | Makes text blue.    |
| `[cyan]`    | `[c]`                        | Makes text cyan.    |
| `[magenta]` | `[m]`                        | Makes text magenta. |
| `[white]`   | `[w]`                        | Makes text white.   |

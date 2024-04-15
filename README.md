# lwu877/school-presentations

A hub for me to present my schoolwork.

---
# FAQs

## What is this... thing?
This "thing" is called a GitHub repository. It contains branches for me to separate a working concept from the final project, and it also allows me to make sure that no one person messes up the entire thing.

## Why are you being difficult?

It's funny. Also, I sent you a link through GitHub Pages. I think you're over thinking this. (hint: click the link I gave you! not dangerous. you can quite literally check the source code to make sure it's not dangerous)

## Why are there two branches?

One is for me/us to work, and the other is where I submit the final project.

## Can't you edit it after you submit it?

Yes, but also no.

Yes, in the sense that we could technically edit it after we've submitted. 

Would we do that? Probably not. And here's a few reasons:

* GitHub shows you the last time anyone updated anything, no matter how small
* If we do have to change something, it's probably minor and it'll be listed on the commits page

## How do I know you didn't just copy and paste from another website?

The way that GitHub works, you can see commits that show you exactly what changed from one version to the next. (Think of it like version history on Google Docs, but it's a lot harder to circumvent.)

You can't accuse me of cheating if I make the source code and the commit history available to the public... and you also can't accuse me of plagiarism if you can just copy and paste the markdown into any old plagiarism checker.

## "Wow, that's cool! How do I use it?"

You're gonna need Visual Studio Code, a GitHub account (optional, but recommended), GitHub Desktop (also optional, but highly recommended) and a little bit of markdown knowhow. (Don't worry, Markdown is suprisingly easy to master. It's like typing on a word document, but you need to remember where to put #s and **s and ---s and brackets).

:exclamation: **Make sure not to skip any steps. If you miss one, this entire thing WILL NOT WORK.**

This is simple to set up and should only take you 15-20 minutes. You can't screw up your computer with this unless you're really trying.

* Download Visual Studio Code. It's available for MacOS, Windows, and Linux. 
  * Alternatively, you can use it on the web at [vscode.dev](vscode.dev)
  * However, exporting your presentation doesn't work on the web, so you're gona need a computer regardless at the end of it all.
  * (think of it as: you can edit on anything, but you need to export on your computer.)
* Create a GitHub account if you haven't gotten one. 
  * Not a shady company. Microsoft (the provider of plenty of things, one being our account system) acquired GitHub back in 2018. 
* Download GitHub desktop. It's available for macOS and Windows.
  * Unofficial ports of the app do exist on Linux. I just... don't need to use them.
  * I find versioning is a lot easier with this tool.
  * If you have any time, I'd be happy to teach you how to use this to its full potential!
* Install the Marp extension on VS Code (shorthand for Visual Studio Code.)
  * It should be the first thing you see.
* Create a GitHub repository. 
  * You can name it anything you want, but I suggest "school-projects" or something of the sort.
* Open that GitHub repository in GitHub desktop.
  * Make sure to "clone" that repository into a new folder. 
  * Why a new folder? Because it's going to be a lot harder to keep track of stuff if it's mixed in with the rest.
  * Also, there's gonna be a lot of heavy work if you're storing anything else in the folder that you're keeping the presentations in.
  * I personally suggest you create a "coding" folder just in case you use GitHub after you finish school.
* Create a Markdown file inside it.
* Include the following text at the beginning.
```
---
marp: true
---
```
It's necessary for formatting purposes. After that, use [this markdown guide](https://www.markdownguide.org/basic-syntax/) to help you understand how to... type in markdown. (It's much simpler than you think.)

In order to begin a new slide, you can insert three dashes (---). Make sure to provide a line break before and after the dashes.

After you're done with everything, commit it into your repository. 

### Final Steps

* Once you're finished with the presentation, export your code as HTML.
* In your GitHub's repository's settings page, make sure to turn on "pages." 
  * You'll receive a page that looks somewhat like "lwu877.github.io"
* In order to access the final file, format the link like this:

[username].github.io/[repository-name]/[presentation-html-name].html

Fill in the blanks, and you have a fully functioning slideshow. 

For customisation offerings (like themes), go to [Marpit's documentation](https://github.com/marp-team/marp-core/blob/main/themes/README.md).

Enjoy!

## Why the hell did you write that?

It was funny.
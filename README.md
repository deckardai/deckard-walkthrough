# How to make your software documentation talk

## Why is inline documentation not good enough?
There are many reasons for that:
* It takes time to read it, because it's in the source code
* Comments are completely unstructured and often not up to date
* It distract you from code, our working memory cannot handle too much

## Why is justWalk better?
Well, it addresses the above issues. Knowledge is not lost, structured, you can discuss it and it does not distract you from writing code.

## Make your documentation talk
Justwalk is an open format for documenting source code, which you can then browse using Deckard. It allows both you and other developers working on the same project to understand it much faster. 

It's very simple!

## How does it work?

You add a **deckardwalk** file to your repository. It basically contains paths and their descriptions. Then the other developers can see and discuss your documentation only when learning about that specific part of code.

The file should look like this:
somedir1/in/repo Some description
somedir2/in/repo Some comment
somedir1/in/somefile2 Write something here
somedir2/in/somefile2 Well, that's a comment!

When you browse your code with your IDE, you double click on a specific keyword and see all the documentation available. Not only for that file, but the entire path.

## Requirements

* You need to download Deckard to browse and comment the documentation. Deckard currently works with Mac and Linux.
* Deckard currently supports Visual Studio Code, IntelliJ, Atom,  Vim. Want to create a plugin? It's simple! Check out our plugin for Atom here: https://github.com/deckardai/atom-deckard 

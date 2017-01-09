# How to make your software documentation talk

## Why is inline documentation not good enough?
There are many reasons for that:
* It takes time to read it, because it's in the source code,
* Comments are completely unstructured and often not up to date,
* It distract you from code, our working memory cannot handle too much.

## Why is justWalk better?
Well, it addresses the above issues: 
* Knowledge is more structured, thus more useful and less often lost,
* You can discuss documentation, which makes it more up-to-date, 
* It does not distract you from writing code-- you have them when you need it.

## Make your documentation talk
Justwalk is an open format for documenting source code, which you can then browse using Deckard. It allows both you and other developers working on the same project to understand it much faster. You document a file or a directory, and others can immediately see and discuss it in Deckard.

It's very simple!

## How does it work?

Simple! Two steps only :-)

STEP 1: You add a **deckardwalk** file to your repository. It basically contains paths and their descriptions. The file (**deckardwalk** should be in the main directory of the repository) should look like this:

```
somedir1/in/repo Some description
somedir2/in/repo Some comment
somedir1/in/somefile2 Write something here
somedir2/in/somefile2 Well, that's a comment!
```

STEP 2: You double click on a specific keyword in your IDE and see all the documentation available in Deckard (either web app or the stand-alone app). Not only for that file, but the entire path. (First double click makes Deckard index your data locally, so you may need to wait, usually less than 30 seconds)

## Requirements

* Just a web browser :-) You will get all the data in the Deckard web app.
* If you want more of Deckard, you can  download install a stand-alone app for either Mac or Linux. The stand-alone app currently supports Visual Studio Code, IntelliJ, Atom,  Vim. Want to create a plugin? It's simple! Check out our plugin for Atom here: https://github.com/deckardai/atom-deckard 

 * To install the stand-alone Deckard app, run
 
 ```
homebrew cask install deckard
```

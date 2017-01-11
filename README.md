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

It takes two steps to do it:

* Add the **deckard.walk** file to the main directory of your repository to turn your documentation into a dynamic one. Look at the example below.
* Open up your new dynamic documentation in:
 * View it in https://assist.deckard.ai and/or
 * Use brew to install Deckard 
 ```
 (brew cask install deckard)
 ```
 * or download the stand-alone Deckard app (and then install your favorite IDE plugin for it) from https://assist.deckard.ai

```
dir1/dir2: |
  This is an example message you will see when you double click
  on the content in this directory

abc/def/somefile.py: |
  Some other message. You will see it when you click on something
  in this file.

one/two/three: |
  This is an example message you will see when you double click
  on the content in this directory

bob/alice/myFile.txt: |
  Some other message. You will see it when you click on something
  in this file.
```

STEP 2: You double click on a specific keyword in your IDE and see all the documentation available in the Deckard web app. If you want to check out of Deckard, install the stand-alone app for either Linux or Mac using 
 ```
homebrew cask install deckard
``` 
NOTE: First double click makes Deckard index your data, so you may need to wait, usually less than 30 seconds
NOTE: Deckard indexes your data locally. It does send it to the cloud.

## Requirements

* Just a web browser :-) You will get all the data in the Deckard web app.
* If you want more of Deckard, you can  download install a stand-alone app for either Mac or Linux. The stand-alone app currently supports Visual Studio Code, IntelliJ, Atom,  Vim. Want to create a plugin? It's simple! Check out our plugin for Atom here: https://github.com/deckardai/atom-deckard 


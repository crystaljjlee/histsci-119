# HISTSCI 119VH: Digital Humanities Component

As part of this course, you will be using StoryMap.js to chart the movement of people, things, and ideas across the world. This tool will help you create an interactive map that you can then embed onto your own website, which will be hosted using GitHub Pages. (It is also possible to embed the StoryMap directly onto platforms like Medium. However, as we will discuss in class, we are asking you to learn how to host these projects using HTML, CSS, and GitHub so that you can have better control of your data, and so that it's easily maintainable.)

## Getting assistance with your project

If you need **technical help**, you can attend the [Harvard Digital Scholarship Support Group (DSSG) office hours](<https://dssg.fas.harvard.edu/event/dssg-office-hours-f19-th/>). If you can't make the office hours, they can assist you remotely or set up a separate appointment. You can also email Jeremy Guillette (jguillette@fas.harvard.edu), the academic technologist for FAS, for additional help (he'll respond quickly during business hours, but won't be available outside of 9–5). He'll definitely help you make the most of StoryMap!

> Before you meet with them, you may also want to consult the [Mozilla Developers Network web docs](https://developer.mozilla.org/en-US/) (guides to [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) and [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)). Someone else may also have had this question on [Stack Overflow](https://stackoverflow.com/) (a high-quality version of Yahoo Answers that is focused primarily on programming).

To discuss the **conceptual components** of your project (especially before you are due to present in class), you can book office hours with me (Crystal) [here](https://crystallee.youcanbook.me/). Before our meeting, be sure to send me a copy of your map so I can have a copy printed out when we meet, and so that we can talk through it in more detail!

## Table of contents

* **[Preliminary Instructions](https://github.com/crystaljjlee/histsci-119/#preliminary-instructions)**
  * [Accounts/applications you'll need](https://github.com/crystaljjlee/histsci-119/#accounts-and-applications-youll-need)
  * [Map resources](https://github.com/crystaljjlee/histsci-119/#resources-for-finding-maps)
* [**Making the StoryMaps**](https://github.com/crystaljjlee/histsci-119/#making-the-storymaps)
  * [Intro to StoryMap](https://github.com/crystaljjlee/histsci-119/#intro-to-storymap-cc)
  * [Intro to Gigapixel](https://github.com/crystaljjlee/histsci-119/#intro-to-gigapixel-cc)
* [**Making your website**](https://github.com/crystaljjlee/histsci-119/#making-your-website)
  * [What is GitHub?](https://github.com/crystaljjlee/histsci-119#what-is-github)
  * [Forking the class repository](https://github.com/crystaljjlee/histsci-119/#forking-the-class-repository)
  * [Activating GitHub pages](https://github.com/crystaljjlee/histsci-119/#activating-github-pages)
  * [Building the website](https://github.com/crystaljjlee/histsci-119/#building-the-website)
  * [Formatting your text](https://github.com/crystaljjlee/histsci-119/#formatting-your-text)

## Preliminary Instructions

### Accounts and applications you'll need

Before you get started with making your StoryMaps, please make sure that you have the following:

1. You will need a personal or a [Harvard-affiliated](https://www.seas.harvard.edu/sites/default/files/files/Education%20and%20Teaching%20Policies/Google%20Harvard%20account%20setup.pdf) **Google account** to save your changes in StoryMap.js.
2. You'll also need a **GitHub account.** Instead of signing up on the general site, make sure to get the [Github Student Developer Pack](https://education.github.com/pack) using your Harvard email. This will give you lots great benefits, like more storage space and the ability to have private repositories.
3. You'll also need to download [**Zoomify Free**](http://www.zoomify.com/free.htm) and [**GitHub Desktop**](https://desktop.github.com/) (available for Mac and PC).

### Resources for finding maps

There are many great online resources for finding high quality maps to use in your project. For our purposes, the bigger and more detailed the map is, the better!

Here are a few places to get you started:

* [David Rumsey Map Collection](https://www.davidrumsey.com/)
* [New York Public Library Map Warper](http://maps.nypl.org/warper/)
* [Boston Public Library's Leventhal Map and Education Center](https://www.leventhalmap.org/)
* [Library of Congress Map Collection](https://www.loc.gov/maps)
* [French National Library](https://gallica.bnf.fr/accueil/en/content/accueil-en?mode=desktop) (use "map" filter in advanced search)
* [Harvard Map Collection](https://curiosity.lib.harvard.edu/scanned-maps?utm_source=library.harvard)
* [John Carter Brown Library Map Collection](https://jcb.lunaimaging.com/luna/servlet/JCBMAPS~1~1)
* [Osher Map Library](https://oshermaps.org/browse-maps?r=5d76b9b179c3c)



## Making the StoryMaps

I've made two videos that introduce you to StoryMap.js – one about the utility more generally, and one that focuses on how to create a StoryMap that uses a historical map.

### Intro to StoryMap [CC]

You can read more about how StoryMap works and see newspaper articles that use the tool [here](https://storymap.knightlab.com/#overview).

[![Intro to StoryMap video still](https://i.imgur.com/mk9vZ8J.png)](https://youtu.be/wZjAc8_VOaY)

### Intro to Gigapixel [CC]

If you don't want to watch a video, you can use this [excellent written tutorial](https://github.com/NUKnightLab/StoryMapJS/blob/master/GITHUB_HOSTING/GITHUB_HOSTING.md) on how to host your tiled images on GitHub.

[![Intro to Gigapixel video still](https://i.imgur.com/HFwhSZr.png)](https://youtu.be/zfhouzPCYBA)

## Making your website

### What is GitHub?

**GitHub** is a tool that software developers use to store and manage code. It is a proprietary service owned by Microsoft, but it uses **git**, an <abbr title="software in which the source code is released under a license where users have the rights to study, change, or distribute software to anyone and for any purpose">open-source</abbr> system system that helps you track changes in source code.   When you start a project in GitHub, you create a *repository,* which you can update with changes that will be tracked automatically in GitHub. 

For this class, you can think of GitHub like file storage similar to Dropbox, where a repository is like a new folder where you can start storing files (in this case, HTML files and images). We'll be hosting the tiled image files for your gigapixel StoryMap and your website using GitHub.

#### Why are we using GitHub and not Wordpress, Medium, or some other content management service (CMS)?

Embedding the StoryMaps is actually a little finicky in Wordpress and other CMS, but it works really well in Medium (the Knight Lab has a collaboration with Medium). Unfortunately, Medium has an extremely poor record [[1](https://www.niemanlab.org/2019/03/the-long-complicated-and-extremely-frustrating-history-of-medium-2012-present/), [2](http://studyhall.xyz/blog/2018/6/12/mediums-mess-the-rise-and-fall-of-the-site-that-was-supposed-to-save-journalism), [3](https://twitter.com/HalimahMarcus/status/998585170314788864)] when it comes to how they pay writers who make content for them, and they retain the rights to share and redistribute whatever you post there.

So, as an exercise in data ownership, we're going to be learning how to make your own web pages. GitHub is proprietary, so that comes with its own issues, but the skills you'll develop here are easily transferrable! Hopefully, your final product will be something that is easily maintainable that you can host wherever you choose (on GitHub or otherwise).

### Forking the class repository

When you are ready to start making your website to host your StoryMap, navigate to the [HISTSCI 119 repository](https://github.com/crystaljjlee/histsci-119). Once you are there, you'll see three buttons at the top right hand side: you want to **fork** this repository, which means that you're copying all of the files into your own account.

!["Watch," "star" and "fork" buttons on GitHub](https://help.github.com/assets/images/help/repository/fork_button.jpg)

This repository is filled with skeleton documents that you are free to customize in order to complete your project. The README file is the document you're reading right now.

### Activating GitHub Pages

Once you have forked the class repo, you'll need to activate GitHub pages so that you'll be able to take your website online. To do so, go to **settings,** navigate to the **GitHub Pages** section, and **select the master branch as the source.**

![screenshot of GitHub pages settings that shows the master branch as source](https://i.imgur.com/PoAfjuu.png)

After you have selected the **source** for your GitHub Pages, you should see the URL where your site will be published, which should be in this format:  `https://<username>.github.io/histsci-119`. You can see the sample that this repo will generate [here](https://crystaljjlee.github.io/histsci-119/).

For your project, you will be customizing **index.html**, which provides a template for the website you will create. The **css** folder *styles* the text in the index file – by providing guidelines for the font color/size, the way that the page is rendered, etc. – and the **images** folder is used to store all the images that you will use for your website. Right now, it contains a **favicon**, which is the little image that you see on the left part of a tab when you're browsing the internet. You can and should customize any part of the template you like (though it certainly isn't necessary).

![Screenshot of HISTSCI 119 repository files, which includes an index.html file and CSS folder](<https://i.imgur.com/2ss0cfi.png>)

[(back to top)](https://github.com/crystaljjlee/histsci-119#table-of-contents)

### Building the website

Once you have forked the HISTSCI 119 repo to your own account and activated GitHub pages, you can get started with editing **index.html**! You can do this directly on the GitHub website – all you need to do is click the index file (which will pull up the source code), and click the pencil icon to edit. (If you prefer to have a little more control, you can also edit the page using a text editor like [Atom](https://atom.io/) and push the file onto GitHub. [Here](https://www.youtube.com/watch?v=6HsZMl-qV5k) is a good video tutorial [CC] on how to use Atom and GitHub together; you can also follow the instructions from the Gigapixel video, where you clone the repository onto your local machine via GitHub Desktop, and open the file using Atom.)

![screenshot of GitHub options when you open a file](https://i.imgur.com/9WUG8MT.png)

However, the most important thing is learning how to **embed the StoryMap in the index.html file,** but it is luckily very easy! When you have finished making your map, the "share" menu on StoryMap gives you code that you can copy and paste directly into the index.html page.

![Image of "share" menu in StoryMaps, which includes code that you can copy and paste into your index.html file](https://i.imgur.com/rAOIjxT.png)



### Formatting your text

From there, you can format the text you write by inserting headers, paragraphs, and lists. All text in HTML needs to be tagged with element names that are surrounded by angle brackets, e.g.:

```html
<h1> This is a heading. </h1>
<h2> This is a subheading. </h2>
<p> This is a paragraph. </p>
```

# This is a heading.

## This is a subheading.

This is a paragraph.

***


Bulleted lists, for example, can be rendered like this:

``` html
<ul>
	<li>Coffee</li>
	<li>Tea</li>
	<li>Milk</li>
</ul>
```

If you copy and paste that code, you will see this on the page:


* Coffee
* Tea
* Milk

For additional examples about how to adjust some more components of your website, you can find a wealth of resources with the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML) and [w3schools](https://www.w3schools.com/).

Happy writing!

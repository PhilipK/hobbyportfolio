+++
title = "BGG Fetch"
date = 2021-02-04
[taxonomies]
tags = ["Rust", "Tokio","Reqwest"]
[extra]
image="../static/images/bggfetch.PNG"
description="20 lines to get all your images from BGG"
+++

A 20 lines program that will make a call to [Boardgame Geek API](https://boardgamegeek.com/wiki/page/BGG_XML_API2), parse the output and print out all the urls pictures of boardgames in a users boardgame collections.
This is used together with the cwget project and the imagemosaic program to make a mosaic wallpaper of images from a users boardgames.

The biggest takeaway from this project was how little code you need to do this. If you know the right crates/libraries to use, you can get a lot done by just stiching them together with a few lines of code.

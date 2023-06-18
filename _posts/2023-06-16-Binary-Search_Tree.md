---
layout: post
title: Binary Search Tree
subtitle: Showcase for BST application
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

This section will cover the binary search tree.

The application I chose to enhance for the Data Structures & Algorithms category was a Binary Search Tree (BST) project from CS 230. For this project, we had to finish developing the application to create and utilize a valid BST and note the times (in clock ticks) of each process, like loading the bids, removing a bid, and displaying all the bids. The original application was able to perform these tasks successfully, but it lacked the ability to display a particular bid, add a bid, and modify bids based on input (it had a hard coded “BID ID” that was used just to make sure the search and delete functions worked).
Enhancements that have been implemented are being able to add a new bid, delete a bid, and display a bid based on the “BID ID”. Another function that was implemented was the ability for the application to check if the BST is empty or the root is “null” before executing any of the functions requiring traversing the tree. It will simply display a message rather than calling a function and returning nothing.
Some additional items that were done were cleaning up some unneeded lines of code that were used for observation purposes. One example is the lines of clock ticks that would show the amount of “clock ticks” it has taken the application to run some of the functions. Some others were removing unused functions and simplifying some of the lines.

Screenshots below showing some of the new functions implemented:


![AddNewBidFunction](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/79529bec-6f48-48a5-b82b-741afb7b5a53)

![IsBSTEmptyFunction](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/b1e98eb8-906c-42d1-9de3-1fdf82b6d2cf)

![CheckIntegerFunction](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/ef0ebaf9-edb8-422a-b5ef-25379d0a7438)

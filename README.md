what2eat
========

Usage
-----
./what2eat

That's all for now.

About
-----
Programmers tend to have weird habbits and I don't know why...

My friends don't want to waste time diciding where to eat, so they spend even more time to pick a random restaurant.

And then there's what2eat, a simple Bash script to help you figure out what to eat tonight.

All choices are in Chinese, but they are easy to understand. So you can make your own choice list easily. For buddies in Xiamen No.1 Middle School, there's also an incomplete list for you. We'll update it from time to time, and if you want to contribute, feel free to do so (both patches and pull requests are OK).

Plan
----
- [x] Weighted shuffling
- [ ] Dynamically adjust weight of each choice
- [ ] Decide what to order
- [ ] Output only the first few lines of the shuffled result

For an up-to-date TODO-list, see the todo file

License
-------
This simple script is licensed under Apache License, Version 2.0.

Note: you don't have to give credit to me if you don't publicly redistrbute my code (or derivative works).

Why the repo contains Mercurial files?
--------------------------------------
Sadly, the mercurial-git package (Wheezy) doesn't work so well for me, so I have to put up with different SCMs.

This repo is actually a Mercurial repo, and Git is only used as a tool to upload/download files to/from Github. That's why the Github repo also includes the .hg directory and the .hgignore file.

Since the Git repo doesn't keep track of the actual commits, it is not supposed to be used as a collaborative tool. However, this script is so simple that patches works just fine.

If you know how to fix the mercurial-git bug or have any good suggestions about a better workaround, please tell me. And sorry again for the inconvenience.

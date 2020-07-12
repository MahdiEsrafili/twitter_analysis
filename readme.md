# Analysis on Twitter

In this repo, I use twitter api with tweepy package.

initial work is to get users following and followers and find mutuals. after that, create a big picture containing mutual friends profile picture.

there is some importants tips:
* there is limit on api usage: 15 req/15 minute. so its better to cache info and not making request if not needed.
* using paging in creating request. for objects with big size, simple requests doesnt give all the information, just 20 of them. so always use pagin!
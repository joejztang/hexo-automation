# description

The aim of this script is to automatize generating and deploying command. Although hexo contributor thinks hexo should perform like it is right now, automated generating and deploying will make my life easier.

By automated generating and deploying, it is easier for me to find syntax error and debug. Actually, the born of this script is due to checking syntax error post by post so many times.

# how to make it work

1. put this script into your hexo folder (project/main folder).
2. change `TIMEOUT` parameter according to your posts' number.
3. change `YOUR_HEXO_DIR` to your hexo project directory.
3. enable `crontab` in terminal by your preference.

# comments

generating of hexo project is slow, try several times and then determine your `TIMEOUT` parameter.

Have fun!

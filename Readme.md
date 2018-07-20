# Maverick Site Template

Welcome to Maverick, a blog engine powered by the [Textbundle](http://textbundle.org) format. To get started with a site of your own, fork this repo and update the [SiteConfig.yml](https://github.com/jsorge/maverick-hello-world/blob/master/SiteConfig.yml) file to suit your needs. To see the commands you can do, check out the [Makefile](https://github.com/jsorge/maverick-hello-world/blob/master/Makefile).

It's really simple to add new posts, just put a textbundle inside of the `Public/_posts` directory. On your server, you can run the `make install-autodeploy` command and configure your repo with a web hook to hit http://your-server:8001. New content will be auto-pushed to your server and deployed within seconds.

If you want to look at the source code for the Maverick engine, [check out the repo here.](https://github.com/jsorge/maverick)
#Jekyll website 

This site is built with jekyll [here](https://github.com/jekyll/jekyll)

This purpose is a test, so it should be adapted to your use.
##Basic configuration 

Run commands shown [here](https://jekyllrb.com/) 

###Known issues

Maybe you'll have an issue when you will execute installation commands. It may be caused because you don't have ruby-dev installed. 
To fixe this, run: 

`sudo apt install ruby-dev -y`

##Deploy with docker 

Run this command in the project directory

`docker run --name newblog --volume="$PWD:/srv/jekyll" -p 3000:4000 -it jekyll/jekyll:4.0.0 jekyll serve --watch --drafts`
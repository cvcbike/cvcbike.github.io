# CUMBERLAND VALLEY COLLECTIVE
### Official website and blog

Here's where our website holds all of its content. 

#### You're probably here to add a blog post. 

1. Create a new file in the '_posts' folder. 
1. Check out [prior blog posts](https://raw.githubusercontent.com/cvcbike/cvcbike.github.io/master/_posts/2020-04-23-hello-world.md) for a feel of formatting in order for the post to work correctly. 
1. Posts are written in Markdown, a text based formatter. [Markdown Cheatsheet.](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


### If you want to make other changes, or you want to see a preview of your post before it goes live, you can test the webiste locally

1. Install [git](https://git-scm.com/).
1. Open Git Bash. 
1. Click the green 'Code' button on the top right of this page and copy the link that's in there.
1. If you opened Git Bash, type `ls` to see the folder you're in. Then type `mkdir CVC` to create a folder called CVC. Then type `cd CVC` to change directory to the new folder. Then, `git clone https://github.com/cvcbike/cvcbike.github.io.git` (no quotes) to download the project. 
1. Now that you have the project, you need a way to run it. Install the Development environment of [Ruby](https://www.ruby-lang.org/en/downloads/)
1. To check if Ruby is installed properly, open up a terminal/command line and type `ruby -v`. If it's not, you may need to restart your computer.
1. Now run `bundle install` when you're in the project folder.
1. Finally run `bundle exec jekyll serve` and then navigate your browser to `localhost:4000`. Congrats! 
1. Now you can make changes to the files. Some files you update will automatically be refreshed on the site, other files you'll need to stop the server (hit `ctrl-c` in the terminal) and restart it to see the changes.

* When you're done and you're sure the changes are good and everything is perfect, just the way you want it to be on the live site, go back to your terminal and do the following
* `git add .`
* `git commit -m 'Your commit message here, basically describe your changes'`
* `git push origin master`
* Then check this page to see your changes. CVC.bike will update in less than a few minutes. 

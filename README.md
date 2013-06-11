picodilly
=========

The project is a client side web application that allows user to create, manage and edit Jekyll blog in Git repo.

Blog source is just a git repo in [Markdown](http://daringfireball.net/projects/markdown/) or 
[Textile](http://textile.sitemonks.com/) human-readable markup.

[Jekyll](http://jekyllrb.com/) generates static site from blog source. It works on [Github Pages](http://pages.github.com/) 
automagically, so we can leverage them for hosting and serving.

The project uses [GitProvider](https://github.com/darvin/git-provider) high-level
implementation-agnostic to access blog source git repo.

For nice blog post editing, project uses [Ace Editor](http://ace.ajax.org/#nav=about)

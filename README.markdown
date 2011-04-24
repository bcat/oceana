Right now, this is just somewhere for me to jot down some thoughts on a new
blogging tool for [my Web site][1]. I would like to actually write this
eventually, but I don't expect to have any code until this summer, at the
earliest.

# Motivation #

To be added...

# Desired features #

*   All static HTML. No server-side processing should happen when someone
    requests a post or page.
*   Real server-side comments. Using [DISQUS][2], etc. is **not** an acceptable
    solution.
*   [Markdown Extra][3] processing for posts, pages, and comments.
*   Support for [LaTeX][4] math markup in posts, pages, and comments.
*   To be completed...

# Ideas for implementation #

*   Implement the site generator in Python.
*   Use [Akismet][5] to mitigate comment spam.
*   To be completed...

[1]: http://bcat.name/
[2]: http://disqus.com/
[3]: http://michelf.com/projects/php-markdown/extra/
[4]: http://www.latex-project.org/
[5]: http://akismet.com/

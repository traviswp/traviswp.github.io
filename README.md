Personal website built on [Jekyll](http://jekyllrb.com/),
inspired by the [Much-Worse](http://jekyllthemes.org/themes/much-worse/) and [Lagrange](https://lenpaul.github.io/Lagrange/) Jekyll themes,
and freely hosted in [Github pages](https://pages.github.com/).

It turns out I'm not easily satisfied with these themes so often try new ones out.
I like this one :)

To ease the burden of switching themes I keep most of *my* data in the `_data/` directory, formatted in YAML files.
I also generally have personal text written in some of the HTML files in the `_includes/` directory
(e.g., `about.html`, `news.html`, `projects.html`, `publications.html`)
and in the markdown files in the root level of this repository
(e.g., `./research.md`, `./projects.md`).

## Quick-Start Guide

If you'd like to use this project as a starting point for your own website,
you are reading in the right section!
Simply fork/clone this repository (or download a zip), and then run `jekyll serve` inside the directory.
This assumes you have Jekyll installed and the files stored locally.
Your site should be up and running locally at [http://localhost:4000](http://localhost:4000).

After you've verified that you can serve the website locally,
edit the site attributes in `_config.yml` and edit the various entries in `_data/`, `_includes/`, and `_posts/` to your liking.
If you push to github, your website should be ready immediately at 'http://USERNAME.github.io'.

In the `_posts` directory you'll find some of my posts as well as good reference posts that I've kept around from the themes that inspired my site.
You can simply duplicate the template post and start adding your own content.

### Debugging

When in doubt a quick and easy way to debug liquid variables is to pipe it into `jsonify` and render the result on the page.
Special thanks to this StackOverflow post (["jekyll debug or print all variables"](https://stackoverflow.com/a/41668125) ) for the suggestion.

```
{{ my.site.variable | jsonify }}
```

where `my.site.variable` is substituted with the variable of interest. 

### Everything Else

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll.
File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].
If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].
If are interested in other themes, check out [Jekyll Themes][jekyll-themes].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
[jekyll-talk]: https://talk.jekyllrb.com/
[jekyll-themes]: http://jekyllthemes.org/

## Copyright & License

Copyright (C) 2017 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

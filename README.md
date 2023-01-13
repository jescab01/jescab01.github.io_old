# Hydejack Starter Kit
A quicker, cleaner way to get started blogging with [Hydejack](https://hydejack.com/).

Hydejack is a template version of Jeckyll, 
in its [documentation](https://hydejack.com/docs/) pages find out more 

## Quick Start
### Running locally
1. Clone repository (git users), or [download] and unzip.
2. Open terminal, `cd` into root directory (where `_config.yml` is located)
3. Run `bundle install` [^1]
4. Run `bundle exec jekyll serve`
5. Open <http://localhost:4000/hydejack-starter-kit/>


## What's next?
* Open files and read the comments
* Read the [docs](https://hydejack.com/docs/)
* Buy the [PRO version](https://hydejack.com/download/) to get the project and resume layout, newsletter subscription box, custom forms, and more.

[^1]: Requires Bundler. Install with `gem install bundler`.

[download]: https://github.com/hydecorp/hydejack-starter-kit/archive/master.zip


----

## How to inset figures in Markdown
Two approaches, the first one may be more efficient, so the reader can have a quick look on the static 
figures before clicking on them and going to a slower loading of the dynamic figures.

1) oppening the figure in another window.
[<img src="/research/th/icon_th.png">](/research/th/figs/Criticality_th_noisy_phetero.html)

2) inserting the figure in the same page.
<iframe width="100%" height="400"
  src="/research/th/figs/Criticality_th_noisy_phetero.html"
  frameborder="0" allow="autoplay; encrypted-media"
  allowfullscreen></iframe>



# blog_posts

Posts for cantuksavul.com: one Jupyter notebook per post, saved with outputs, named `YYYY-MM-DD-title.ipynb`.

The site repo mounts this repo as its `posts/` submodule and builds this repo's `main` head. Every push to `main` runs `.github/workflows/deploy-site.yml`, which starts the site's deploy workflow through a token that can only run workflows there.

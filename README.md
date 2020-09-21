

## How to create a similar site?

Create a new repo on github, use template https://github.com/wowchemy/starter-academic


## Develop and test site locally:

    docker run --rm -it --name "curk.info" -p 1313:1313 -v $(pwd):/src klakegg/hugo:0.74.3-ext server --disableFastRender --i18n-warnings

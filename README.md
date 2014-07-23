dubhacks.co
===========

![dubhacks.co](https://cloud.githubusercontent.com/assets/744973/3140995/1e99525e-e95a-11e3-827d-36a758a0bf12.png)

### Development

`master` is the production branch which is deployed as changes are pushed. Never develop on `master`.

Make new branches for new changes, and once you are satisfied, merge them with `master` and push them.

### Installing

```sh
git clone git@github.com:dubhacks/dubhacks.github.io.git
npm install                # install dependencies
```

### Continuous Building

Commands to run to build and serve the file (use separate tabs):

```sh
grunt watch                # run grunt tasks on changes
jade -w -P index.jade      # process jade on changes
python -m SimpleHTTPServer # serve the site locally
```

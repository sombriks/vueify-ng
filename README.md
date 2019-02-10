# vueify-ng

The next generation, community-driven fork of original vueify transformation for
browserify setup with newest vue releases

## Rationale

Browserify + Budo for development and Browserify + tinyify for production are a
blazing success either for fast prototyping or big industrial setup projects.

Therefore i see a huge valor in keeping it up to date and running well.

Since original vueify was sent to the attic, the community shall handle it now,
creating patches as writing tests for it. Pretty much the same what happened to
other key libraries, vue-resource for instance: axios, the community solution
was preferred over it.

So what now?

Since vueify-ng is way more focused than a rest client, we must be more humble
and just keep it up to date and well tested.

## Key targets

This fork aims on these objectives:

- harvest pending patches from original vueify repository
- keep an up to date browserify transform (i.e. latest babel, stylus, pug, scss,
  etc)
- provide test cases for every possible scenario. I hope so.
- quickly approve patches with test cases and make a release of it

## The future

I really hope to demonstrate how things got way better on browserify realm since
budo and tinyify came and we got rid of nasty things like gulp/grunt. A Makefile
can do better.

Keep vue a first class citizen on browserify ecosystem is a key feature for
better and faster setups.

## Contributing

Just fork, set this repo as your upstream to regularly pull updates and send
your pull requests, we'll review and eventually merge them. After three decent
merges you'll get commit access to the core repo (unless i don't trust you, who
knows why)

## Original work

All this code was originally written and petted by
[Evan You](https://github.com/yyx990803) and many other
[contributors](https://github.com/vuejs/vueify/graphs/contributors).

## License

This keeps the original MIT license.

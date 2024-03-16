# @aiktb/kuromoji

# Why need this fork?

This is a special purpose version of kuromoji that allows serving `*.dat` instead of `*.dat.gz` files.
The logic about file decompression has been removed from the code. If you are curious why this is needed, please check https://github.com/aiktb/FuriganaMaker/issues/21.

# Why forked by @sglkc/kuromoji?

@aiktb/Kuromoji forked by [@sglkc/kuromoji](https://github.com/sglkc/kuromoji.js), @sglkc/kuromoji forked by kuromoji.js.

@sglkc/kuromoji is a very good kuromoji fork. Now that kuromoji.js has stopped maintaining, it provides many modern features, such as browser support, service worker support, etc. For details, please check my blog:
[Stop Using kuromoji.js: @sglkc/kuromoji is a Better, More Modern Fork](https://aiktb.dev/blog/better-kuromoji-fork)

> [!CAUTION]
> This fork has no long-term maintenance plans and has only been tested in the browser. No issues will be accepted.
> If you need anything, please create a fork or open a PR.

# How to use

Compatible with [kuromoji.js API](https://github.com/takuyaa/kuromoji.js), the only difference is that please provide the directory where the `*.dat` files are stored.
# Bones.

> _The most simple blog you'll find out there._

Inspired by http://motherfuckingwebsite.com/.


## Installation.

After cloning this repository, `cd` into it and run:

```
ln -sfr .reindex .git/hooks/pre-commit
```

`.reindex` rebuilds the index each time a commit is made. You don't
have to worry about keeping your `index.html`'s index up to date.


## Usage.

Create a new post by running `./newpost <title>`. `"$EDITOR"` will be
lauched and you can then write your post.

# Bones.

> _The simplest blog you'll find out there. (Inspired by http://motherfuckingwebsite.com/)._


## Installation.

After cloning this repository, `cd` into it and run:

```
ln -sfr .reindex .git/hooks/pre-commit
```

`.reindex` rebuilds the blogs index each time a commit is made.
Blogs will be sorted from newest to oldest.

You can then edit `index.html`, adding your own information.

## Usage.

Create a new post by running `./newpost <title>`. `"$EDITOR"` will be
lauched for you to write your post.

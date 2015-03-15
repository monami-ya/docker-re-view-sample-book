Re:VIEW sample book
===================

This is an sample repository.
You'll get 'ReVIEW sample book' written by @takahashim.

How to build (the sample book).
-------------------------------

```sh
git clone https://github.com/monami-ya/docker-re-view-sample-book.git
docker run --rm -v `pwd`/src:/review monami0ya/docker-re-view
```

You'll get ```src/book.pdf``` and ```src/book.epub``` after docker container is finished.

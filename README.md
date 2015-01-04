webhook-test
============
This is a test of a post-commit webhook I'm developing.
When you commit in ``master`` it checks whether the commit contains any pdfs.
If so, it checks out the pdfs from master to the ``gh-pages`` branch and then commits them using the same commit message from the master commit.
This repo doesn't contain the post-commit script itself.
To view that script, see my [bin](https://github.com/fditraglia/bin) repository: it's called ``checkout-pdfs``.
This repo is only for testing purposes.

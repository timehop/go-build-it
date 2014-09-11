go-build-it
===========

Quick utility script to be able to build Go binaries from Travis builds

Usage
-----

Environment Variables Required:

* `TRAVIS_REPO_SLUG`
* `TRAVIS_BUILD_NUMBER`
* `AWS_ACCESS_KEY_ID`
* `AWS_SECRET_ACCESS_KEY`
* `AWS_S3_BUCKET`

To build:

```
./lets build cmd/worker/main.go worker
```

To upload:

```
./lets upload
```

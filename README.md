# Codeminer42 Python Images for CI builds

Docker Python images used by our CI.

## Dependencies

The following dependencies are being installed on all images:

* ...
* ...

## Tags

We currently have images for the following versions:

- `?`, `latest` [Dockerfile]()

## Contributing

`Dockerfiles` are stored under folders for each version.

For updating the images, just open a _pull request_ with
the new `Dockerfile` version and, after accepted, Docker
Hub will build automatically after a few minutes.

The images should setup an environment that is widely used,
please don't install dependencies that are specific to a
project. It's also good to have a pattern and all images
support the same things, why a ruby version would use
PhantomJS and the other doesn't?

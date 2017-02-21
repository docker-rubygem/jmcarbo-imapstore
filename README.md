[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/jmcarbo-imapstore.svg)](https://hub.docker.com/r/rubygem/jmcarbo-imapstore/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/jmcarbo-imapstore.svg)](https://hub.docker.com/r/rubygem/jmcarbo-imapstore/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/jmcarbo-imapstore.svg)](https://hub.docker.com/r/rubygem/jmcarbo-imapstore/)
[![Gem Downloads](https://img.shields.io/gem/dt/jmcarbo-imapstore.svg)](https://rubygems.org/gems/jmcarbo-imapstore/)
# jmcarbo-imapstore

Auto-Generated Docker image for jmcarbo-imapstore to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/jmcarbo-imapstore`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/jmcarbo-imapstore`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/jmcarbo-imapstore`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/jmcarbo-imapstore/)

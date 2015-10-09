# Environment variables in popular Continuous Integration systems

[![Build Status](https://travis-ci.org/wkoszek/ci-env.svg?branch=master)](https://travis-ci.org/wkoszek/ci-env)

This repo is supposed to help you understand how Travis workers are
configured, so that you can take full advantage out of their environment.

# How it works

This repo is wired to Travis Ci. It simply called `printenv` and `set`, so
that you can see the CI worker's configuration. Just click the badge of the
respective CI system to see what environment variables are set.

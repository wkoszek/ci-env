# Environment variables in popular Continuous Integration systems

This repo is supposed to help you understand how Travis, Circle CI and
AppVeryor workers are configured, so that you can take full advantage out of
their environment.

For me one of the problems with CI systems is that they're more like
debugging an issue through a key-hole.

# How it works

This repo is wired to all 3 systems:

- Travis CI [![Build Status](https://travis-ci.org/wkoszek/ci-env.svg?branch=master)](https://travis-ci.org/wkoszek/ci-env)
- Circle CI [![Circle CI](https://circleci.com/gh/wkoszek/ci-env/tree/master.svg?style=svg)](https://circleci.com/gh/wkoszek/ci-env/tree/master)
- AppVeyor [![Build status](https://ci.appveyor.com/api/projects/status/5yowbhiqd8e3qj4w?svg=true)](https://ci.appveyor.com/project/wkoszek/ci-env)

It simply called `printenv` and `set`, so that you can see the CI worker's
configuration. Just click the badge of the respective CI system to see what
environment variables are set.

# Big thanks to guys from Travis CI, Circle CI and AppVeyor

I have 40+ GitHub repos wired to all 3 of them. All for 3. The service is
great. Other than some usual hiccups and user errors, I haven't had any
complaints. This repository is trying to address problems typical for CI
systems.

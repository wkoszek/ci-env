# Environment variables in popular Continuous Integration systems

This repo is supposed to help you understand how workers for popular
Continuous Integrations systems are configured, so that you can take full
advantage out of their environment.

For me one of the problems with CI systems is that they're more like
debugging an issue through a key-hole: you change the config, run a
long-running job and wait to see a bug. You modify 1 line and retry. And
sometimes it's unclear why things are certain way.

# How it works

Code in this repo gets build in the CI service environment. All CI systems
used here are free for Open Source projects. The code simply calls
`printenv` or `set` so that you can see the CI worker's configuration. Just
click the badge of the respective CI system to see what environment
variables are set.

This repo is wired to all 3 systems:

- Travis CI: https://travis-ci.org/
- Circle CI: https://circleci.com/
- AppVeyor: http://www.appveyor.com/

CI system | Status
------------- | -------------
Travis CI | [![Build Status](https://travis-ci.org/wkoszek/ci-env.svg?branch=master)](https://travis-ci.org/wkoszek/ci-env)
Circle CI | [![Circle CI](https://circleci.com/gh/wkoszek/ci-env/tree/master.svg?style=svg)](https://circleci.com/gh/wkoszek/ci-env/tree/master)
AppVeyor | [![Build status](https://ci.appveyor.com/api/projects/status/5yowbhiqd8e3qj4w?svg=true)](https://ci.appveyor.com/project/wkoszek/ci-env)

# Big thanks to guys from Travis CI, Circle CI and AppVeyor

I have 40+ GitHub repos wired to all 3 of them. All for 3. The service is
great. Other than some usual hiccups and user errors, I haven't had any
complaints. This repository is trying to address problems typical for CI
systems. CircleCI helped me get my website http://www.koszek.com to a better
quality before I was ready to publish it. AppVeyor let me revive old Windows
software I wrote during my university years.

# Author

- Wojciech Adam Koszek, [wojciech@koszek.com](mailto:wojciech@koszek.com)
- [http://www.koszek.com](http://www.koszek.com)

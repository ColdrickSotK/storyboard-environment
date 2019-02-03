# StoryBoard Development Environment

This repository contains a docker-compose file which spins up all
the services needed to have a fully-functional development environment
for [StoryBoard][0].

It also contains a StoryBoard configuration file which sets up an
instance to work with the services created with docker-compose.

To use,

    docker-compose up -d

And copy `storyboard.conf` to `/path/to/storyboard/etc/storyboard.conf`
instead of steps 4 and 5 of the [developer setup guide][1]. The steps
for installing and setting up MySQL in that guide can also be skipped.

[0]: https://docs.openstack.org/infra/storyboard/
[1]: https://docs.openstack.org/infra/storyboard/install/development.html

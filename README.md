# veewee-berkshelf

Veewee definitions for rapid cookbook iteration with Berkshelf and Vagrant

# Requirements

* Ruby >= 1.9.2
* Bundler >= 1.2.0
* VirtualBox ~> 4.2.0

## Setup

## Building boxes

    $ bundle install
    $ bundle exec veewee vbox build Berkshelf-CentOS-6.3-x86_64-minimal

## Packaging boxes

    $ bundle exec vagrant basebox export Berkshelf-CentOS-6.3-x86_64-minimal 

## Authors

Author:: Jamie Winsor (<jamie@vialstudios.com>)

Copyright 2012 Jamie Winsor

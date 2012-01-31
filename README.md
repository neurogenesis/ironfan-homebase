# jruby chef cookbook

Installs/Configures jruby

## Overview

A very basic recipe to install jruby-1.5.6 from a downloaded tarball.

## Recipes 

* `default`                  - Base configuration for jruby
* `gems`                     - Gems

## Integration

Supports platforms: debian and ubuntu

Cookbook dependencies:
* java
* install_from


## Attributes

* `[:jruby][:home_dir]`               - Installed location of jruby (default: "/usr/local/share/jruby")
* `[:jruby][:release_url]`            - JRuby release tarball to install (default: "http://jruby.org.s3.amazonaws.com/downloads/:version:/jruby-bin-:version:.tar.gz")
* `[:jruby][:version]`                -  (default: "1.6.5")
* `[:jruby][:ruby_version]`           -  (default: "1.9")
  - what version of ruby to behave like
* `[:java][:java_home]`               -  (default: "/usr/lib/jvm/java-6-sun/jre")

## License and Author

Author::                Jacob Perkins - Infochimps, Inc (<coders@infochimps.com>)
Copyright::             2011, Jacob Perkins - Infochimps, Inc

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

> readme generated by [cluster_chef](http://github.com/infochimps/cluster_chef)'s cookbook_munger

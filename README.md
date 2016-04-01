# d3 - Command line package and patch management for Casper

d3 is a package deployment and patch management system for OS X that enhances the
[Casper Suite](http://www.jamfsoftware.com/products/casper-suite/), an enterprise-level management system for Apple devices from [JAMF Software](http://www.jamfsoftware.com/). It was created by [Pixar Animation Studios](http://www.pixar.com/).



d3 adds these, capabilities and more, to Casper's package handling:

* Automatic software updates on clients when new versions are released on the server
* Pre-release piloting of new packages
* Customizable slideshow presented during logout/reboot installs
* Installs and uninstalls are conditional on the exit status of pre-flight scripts
* Packages can be expired (auto-uninstalled) after a period of disuse
* Both the client and admin tools are command-line only and fully scriptable
* Admin command-line options allow integration with developer workflows and package-retrieval tools

d3 is written in Ruby and available as a rubygem called ['depot3'](https://rubygems.org/gems/depot3). It interfaces with Casper mostly via it's REST API using [ruby-jss](https://github.com/PixarAnimationStudios/ruby-jss), a ruby module that provides simple and powerful access to the API. It also uses Casper's backend MySQL database directly to provide enhanced features.


Please see the [wiki](https://github.com/PixarAnimationStudios/depot3/wiki) for full documentation

The developer documentation for the D3 ruby module is at [http://www.rubydoc.info/gems/depot3](http://www.rubydoc.info/gems/depot3)

Also check out [ruby-jss](https://github.com/PixarAnimationStudios/ruby-jss), which is used by d3, but is useful for working with the Casper REST API in any project. 


## CONTACT

[Email the developer](mailto:d3@pixar.com)

[Macadmins Slack Channel](https://macadmins.slack.com/messages/#d3/)

## LICENSE

Copyright 2016 Pixar

Licensed under the Apache License, Version 2.0 (the "Apache License")
with the following modification; you may not use d3 except in
compliance with the Apache License and the following modification to it:

Section 6. Trademarks. is deleted and replaced with:

> 6\. Trademarks. This License does not grant permission to use the trade names, trademarks, service marks, or product names of the Licensor and its affiliates, except as required to comply with Section 4(c) of the License and to reproduce the content of the NOTICE file.

You may obtain a copy of the Apache License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the Apache License with the above modification is
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied. See the Apache License for the specific
language governing permissions and limitations under the Apache License.

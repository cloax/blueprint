# `blueprint` reverse engineers servers for you:

* See what's been installed.
* Standardize development environments.
* Share stacks with your team.
* Generate configurations for Puppet or Chef.
* Audit your infrastructure.

`blueprint` is DevStructure's workhorse tool that looks inside popular package managers, finds changes you made to configuration files, and archives software you built from source to generate Puppet, Chef, or shell code.  Everything blueprint sees is stored in Git to be diffed and pushed.  It runs on Ubuntu Linux 10.04 and newer.

## Try it now!

	git clone git://github.com/devstructure/blueprint.git
	cd blueprint
	make && sudo make install

Not sure what to do next?  The [tutorial](http://devstructure.com/tutorial.html) will take you from setup all the way to production with a simple web application.

## Contribute

`blueprint` is BSD-licensed.  We love bug reports and pull requests!

* [Source code](https://github.com/devstructure/blueprint)
* [Issue tracker](https://github.com/devstructure/blueprint/issues)
* [Documentation](http://devstructure.github.com/blueprint/)
* [Discuss](https://groups.google.com/forum/#!forum/blueprint-users) or `#devstructure` on Freenode

Contributing to Ladybug Tools Projects
=========================================

Thank you for considering contributing to Ladybug Tools. We welcome contributions to all
our [projects on Github](http://www.github.com/ladybug-tools) and from anyone, even if
you are new to open source we will be happy to help you to get started. Most of the
Ladybug Tools developers started learning programming through developing for Ladybug Tools.

Issues
------
Feel free to submit issues and enhancement requests to each repository.

Contributing
------------
Please refer to each project's contributing file for style guidelines. In general, we
follow the "fork-and-pull" Git workflow.

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Push** your work back up to your fork
 5. Submit a **Pull request** so that we can review your changes

If you don't know what is Git read the section for [new users](#new-users).

NOTES:
 1. Be sure to open an issue or contact the current developers and let them know about your
 desire to work on the project. This will ensure that no one else is working on the same
 problem and also provides the opportunity for us to help you to get started with development.
 2. Be sure to merge the latest from "upstream" before making a pull request!
 3. An acceptable **Pull request** should not be more than 200 lines of changes otherwise
 it will be very hard for us to review the code.
 4. Read the contributing.md of the project beforehand to ensure your pull request meets
 the requirement of the project.

Style guide
-----------
For Python projects see Ladybug Tools [Python style guide](
https://github.com/ladybug-tools/contributing/wiki/python-style-guide).
 
Please also take a look at the zen of Python by Tim Peters. To read the Zen of Python, please write 
```import this``` in your Python shell and run it.

Unit conventions
-----------
All Ladybug Tools repositories follow a convention of assuming SI units by default. Accordingly, all
properties on objects and all inputs to functions within a repository are expected to be in SI.

For developers needing to convert the inputs or outputs of Ladybug Tools repositories to other unit systems
for front-end interfaces, ladybug-core includes a [dataype module](https://github.com/ladybug-tools/ladybug/tree/master/ladybug/datatype) that is capable of converting between many types of units. 
Furthermore, all geometry objects of [ladybug-geometry](https://github.com/ladybug-tools/ladybug-geometry)
possess `scale` methods that can be used to scale the geometry to/from meters.

For angular inputs and outputs, all Ladybug Tools repositories use degrees (as opposed to radians) with
the only excpetion being [ladybug-geometry](https://github.com/ladybug-tools/ladybug-geometry), which
uses radians for faster trigonometric operations and better compatability with CAD interfaces.

Licensing
-----------------------
Most of the Ladybug Tools repositories are open source under the GNU General Public License v3.0.
unless indicated otherwise. For more information about the license see [here](https://github.com/ladybug-tools/honeybee/blob/master/LICENSE).

New Users
---------
The first thing to do is to register a user name with [GitHub]( https://github.com/ ).

You will need to supply a username and email address and to create a password.

After you have registered you can go to your [GitHub settings]( https://github.com/settings/profile ).
Here you can add a photo and update your bio. It's a good thing to add at least some
data - especially a photo and a location. These help your friends remember and know
that it is really you.

If you are new and looking for some way to contribute a good place to start is to look
at the issues tagged **good first issue**.

See [contributing notes for Spider project](http://www.ladybug.tools/spider/#pages/contributing.md)
to learn how to become a team member and be a good citizen!

FAQ
---
See [here](http://www.ladybug.tools/about.html#faq) for FAQ.
If you can't find your question [open a new issue](https://github.com/ladybug-tools/contributing/issues/new).

Be nice!
--------
Please note that all participants of this project are expected to follow our
Code of Conduct. We enjoy the development of Ladybug Tools and want to make it enjoyable
for others. We care about good code but value our community and the people over the code
and development. By participating in Ladybug Tools project you agree to abide by its terms.
See [our code of conduct](CODE_OF_CONDUCT.md).


### Thank you and happy coding! :)

#  WordPress Plugin Boilerplate !

This is a Hard Fork of the [WordPress Plugin Boilerplate](https://github.com/sbtechbd/WordPress-Plugin-Boilerplate).
The **WordPress** WordPress Plugin Boilerplate actively takes PRs and is maintained and under active development, as well as has more features than the original.
The goal is still a standardized, organized, object-oriented foundation for building high-quality WordPress Plugins, however actively accepting cooperation, and also considering ClassicPress Compatibility.

In the case ClassicPress and WordPress diverge too much in the future we will consider creating a new, standalone repo just for ClassicPress. However, as it stands of today, 2021-07-9 (9th July 2021) the Codebase of both CMS is still compliant.

A Generator Plugin to generate new Plugins by filling out a form is available [here](https://github.com/TukuToi/tukutoi-plugin-generator) and acts like a WordPress Plugin.
It can be used to *generate* a Plugin based on *any* boilerplate source really, but uses by default the Better WordPress Plugin Boilerplate.

The generator form will soon be online on a standalone website as well.

## Features

* The Boilerplate is based on the [Plugin API](https://codex.wordpress.org/Plugin_API), [Coding Standards](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/), and [Documentation Standards](https://developer.wordpress.org/coding-standards/inline-documentation-standards/).
* The plugin is 100% [WPCS (WordPress Code Sniffer)](https://github.com/WordPress/WordPress-Coding-Standards) Compliant.
* The plugin is scanned by SonarCloud (see SonarCloud badges on top of the readme)
* All classes, functions, and variables are documented so that you know what you need to change.
* The Boilerplate uses a strict file organization scheme that corresponds both to the WordPress Plugin Repository structure, and that makes it easy to organize the files that compose the plugin.
* The project includes a `.pot` file as a starting point for internationalization.

## How to Create a Plugin

The Better WordPress Plugin Boilerplate (everything *inside and inclusive* the folder `plugin-name` of this repo) can be installed directly into your plugins folder "as-is". 

You will want to rename it and the classes and methods inside of it to fit your needs. 
Some comments inside the Boilerplate may need to be rewritten as well and adapted to your code/use case.

For example, if your plugin is named 'example-me' then:

* rename files from `plugin-name` to `example-me`
* change `plugin_name` to `example_me`
* change `plugin-name` to `example-me`
* change `Plugin_Name` to `Example_Me`
* change `PLUGIN_NAME_` to `EXAMPLE_ME_`

It's safe to activate the plugin at this point. 
Because the Boilerplate has no real functionality there will be no menu items, meta boxes, or custom post types added until you write the code, of course.

For simplicity, you can just use the [Boilerplate Generator Plugin](https://github.com/sbtechbd/WordPress-Plugin-Boilerplate), or the Webform (coming soon), to generate a starter plate using your file-, class-, method- names (and prefixes, author name, etc etc).

## Submit a Plugin to WordPress.org

[Comin soon] instructions and example folder boilerplate to use when submitting a plugin to WordPress.

# What About Contributing?

Submit your idea to the [Discussions](https://github.com/sbtechbd/WordPress-Plugin-Boilerplate) for the community to approve. Each Idea needs at least 2 distinct thumbs up (*additional* to the OP) to be considered for implementation. 

Additionally to the Discussions Post, if you have a working code to implement your Idea, please add a PR **to the develop branch**.
PR'd ideas still need at least 2 additional thumbs up in the Discussion post to be merged. 

Note that in special cases (security, quality, yada yada) we may or may not merge the code and may or may not add or remove features discussed at our own will, independent from the amoung of thumbsup.

The Better WordPress Plugin Boilerplate follows PHP, WP Coding standards and has the Git Actions for it incorporated.


## Documentation, FAQs, and More

If you’re interested in writing any documentation or creating tutorials please let's discuss.


# Credits

The WordPress Plugin Boilerplate was started in 2011 by [Subrata Debnath](https://github.com/subrata6630) and has since included a number of great contributions. 
We saw an opportunity here to continue a great project and develop it further, also with great ideas for the community itself.

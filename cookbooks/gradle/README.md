# Gradle Chef Cookbook

This is an OpsCode Chef cookbook for Gradle, a modern build tool.

It uses officially released tarballs to install Gradle under /usr/local/gradle,
provides an `/etc/profile.d` script that prepends Gradle's `bin` directory to
the `$PATH` and allows you to tweak version using Chef node attributes.

Unlike some other Chef cookbooks, this cookbook is released under the MIT
license.  Feel free to redistribute, use in commercial projects and modify to
your needse.

## Recipes

Main recipe is `gradle::default`.

## Supported OSes

Debian and Ubuntu (any version that was released in the last 1-2 years and
provides Groovy package should work fine).

## Dependencies

OpenJDK 6 or Sun JDK 6.


## Copyright & License

2012 Michael S. Klishin
2013-2015 Travis CI GmbH

Released under the [MIT
license](http://www.opensource.org/licenses/mit-license.php).

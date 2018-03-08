# Ubuntu Touch QML Go App Template

A template to generate apps for Ubuntu Touch that are QML apps with a Go backend
and uses [clickable](http://clickable.bhdouglass.com/en/latest/) to compile it.

## Usage

To get started with this template, simply run `clickable init` and choose the
'Go/QML App' option.

### OR

* Install the needed tools
    * [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/)
    * [clickable](http://clickable.bhdouglass.com/en/latest/)
* Setup your `GOPATH` env variable
* Generate the project
    * Run `cookiecutter gh:bhdouglass/ut-app-go-template`
* Go into the directory for your new project
* Run `go get -d .` to install go dependencies
* Run `clickable` to compile and install your new app!

## License

Copyright (C) 2018 [Brian Douglass](http://bhdouglass.com/)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 3, as published
by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranties of MERCHANTABILITY, SATISFACTORY QUALITY, or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.

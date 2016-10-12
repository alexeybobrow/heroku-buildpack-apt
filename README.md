# heroku-buildpack-apt

Add support for apt-based dependencies during both compile and runtime.

## Usage

Include a list of apt package names to be installed in a file named `Aptfile`

## Example

#### .buildpacks

    https://github.com/abulava/heroku-buildpack-apt
    https://github.com/heroku/heroku-buildpack-ruby

#### Aptfile

    libpq-dev
    http://downloads.sourceforge.net/project/wkhtmltopdf/0.12.1/wkhtmltox-0.12.1_linux-precise-amd64.deb

## License

[MIT](http://mit-license.org)

\<copyright holders\> are [David Dollar](https://github.com/ddollar), [Andrey Bulava](https://github.com/abulava) and other contributors.

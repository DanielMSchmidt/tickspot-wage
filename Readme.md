Tickspot-Wage
=============

# Description

A cli for getting the hours worked and money gained via the tickspot API.
It saves a configuration file under `~/.wageconfig`, including your tickspot credentials and your hourly wage.
There is a config command (`wage config <property> <value>`) to change these properties (company, email, password, wagePerHour).

# Usage

To install wage from npm, run:

```
$ npm install -g tickspot-wage
```

Run ```wage --help``` to get the existing commands (`wage month` for now).

To install the bash completion run `wage completion >> ~/.bashrc  (or ~/.zshrc or ~/.bash_profile)`

# License

Copyright (c) 2015 Daniel Schmidt

[MIT License](http://en.wikipedia.org/wiki/MIT_License)

# Acknowledgments

Built using [generator-commader](https://github.com/Hypercubed/generator-commander).

[![Stories in Ready](https://badge.waffle.io/EinD/EinD.github.io.png?label=ready&title=Ready)](https://waffle.io/EinD/EinD.github.io)

![EinD Logo](logos/EinD-logo.png)

This repository contains the source for the EinD.io website; visit the
[core repository](https://github.com/EinD/EinD.github.io) for details on
the EinD project.

## Contributing
...

## Setup

### Installing Ruby gems
`sudo gem install bundler` to get bundler, then you can just `bundle install` to install all the gems.

### Serving locally
```
jekyll serve --watch
```
Open on `http://localhost:4000`

### Running tests
```
bundle exec rake test
```

### (Optionally) Regenerate dependencies
Install bower if you don't have it:
```
npm install bower
```
Then install the JS dependencies with `bower install`.

## License

&copy; 2014 Cameron Eagans and Josh Branchaud

Licensed under the MIT License. See LICENSE for details.

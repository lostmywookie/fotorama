
# Fotorama by Andrés Bott
I forked this awsome project to work on features i want in this project.
feel free to ouse it.

<h3>Features I aded:</h3>
<h4>- Img Space:</h4>
add space between image and stage (container) 
```
<div class="fotorama"
    ...
    data-imgspace="10%"
    ...
>
```
<h4>- Percent height:</h4>
on original fotorama, if you use an percent value for height, it will take the height of the window as reference to calculate the height. 
I modified it to check if the parent has an asociated heigt. and use this height instead.
```
<div class="fotorama"
    ...
    data-height="100%"
    ...
>
```

as I keep using if, sure more will come...

<hr>
<h6>Readme from original project:<H6>
# Fotorama source

There is nothing for non-coders. Take the latest and ready-to-use Fotorama on its website:<br>
> **http://fotorama.io/set-up**

## How to build
First, ensure that you have the latest [Node.js](http://nodejs.org/) and [npm](http://npmjs.org/) installed.

Test that Grunt’s CLI is installed by running `grunt --version`.  If the command isn’t found, run `npm install -g grunt-cli`.  For more information about installing Grunt, see the [getting started guide](http://gruntjs.com/getting-started).

1. Fork and clone the repo.
2. Run `npm install` to install all dependencies (including Grunt).
3. Run `grunt` to grunt this project.

if you're getting "Warning: spawn ENOENT Use --force to continue." it's probably you don't have sass installed: run sudo gem install sass

Hack on by running `grunt watch` and editing files in the `src/` subdirectory.

The built version of Fotorama will be put in the `out/`.

## Submitting pull requests
1. Create a new branch, please don’t work in your `master` branch directly.
2. Add stuff.
3. Push to your fork and submit a pull request to Fotorama’s `develop` branch.

Regarding code style like indentation and whitespace, follow the conventions you see used in the source already.

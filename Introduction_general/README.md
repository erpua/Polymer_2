# \<polymer-component\>

Intorduction Lesson

Polymer SETUP:

Make sure you have installed a version of Node.js supported by Polymer. To check the version of Node.js that you have installed, run:

- node --version
  See the official node version support policy for more details.

Update npm.

- npm install npm@latest -g
  Ensure that Git is installed.

- git --version
  If it isn't, you can find it on the Git downloads page.

Install the latest version of Bower.

- npm install -g bower
  Install Polymer CLI.

npm install -g polymer-cli

- polymer init
  ? Which starter template would you like to use?

1. polymer-3-element - A simple Polymer 3.0 element template
2. polymer-3-application - A simple Polymer 3.0 application
3. polymer-3-starter-kit - A Polymer 3.x starter application template, with navigation and "PRPL pattern" loading
4. polymer-2-element - A simple Polymer 2.0 element template
5. polymer-2-application - A simple Polymer 2.0 application
6. polymer-2-starter-kit - A Polymer 2.x starter

? Element name (Polymer_2-element) qwe
Custom element names must contain a hyphen. Example: unicorn-cake
Please try again.
? Element name ievgen-element
? Brief description of the element (press Enter if no description)

bower installation process ...

After completed:

- bower install ( all dependencies / might be automatic)

- polymer serve

MARKUP TIPS:

-"ul > li \* 3 { item \$} " => without backslash

<ul>
 <li>item 1</li>
 <li>item 2</li>
 <li>item 3</li>
 </ul>

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

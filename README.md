# chrome-cli

Open Google Chrome from the command line.

## Installation

```sh
npm install -g chrome-cli
```

## Usage

`chrome` launches and passes its arguments directly to Google Chrome.

```sh
# Open a new window
chrome

# Open a new "incognito" window
chrome --incognito

# Open a local file
chrome file.html

# Open a URL, incognito
chrome google.com --incognito
```

## Caveats

* Only macOS is supported right now.
* This assumes that Chrome is installed in `/Applications/Google Chrome.app`

## Options

Here are some lists of arguments supported by Google Chrome:

* [A list of useful Google Chrome command line switches - gHacks Tech News](https://www.ghacks.net/2013/10/06/list-useful-google-chrome-command-line-switches/)
* [List of Chromium Command Line Switches « Peter Beverloo](http://peter.sh/experiments/chromium-command-line-switches/)

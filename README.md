# chrome-cli

Open Google Chrome from the command line.

**Note:** Only macOS is supported right now.

## Installation

```sh
npm install -g chrome-cli
```

## Usage

The `chrome` command launches and passes its arguments directly to Google Chrome.

```sh
# Open a new window
chrome

# Open a new "incognito" window
chrome --incognito

# Open a local file
chrome file.html

# Open a URL, incognito
chrome https://google.com --incognito
```

By default, this assumes that Chrome is `/Applications/Google Chrome.app`.

To point elsewhere, set the `CHROME` environment variable to the path of your Chrome installation's app bundle. For example, if you use Chrome Canary, you can add the following to your `.bashrc`:

```sh
export CHROME='/Applications/Google Chrome Canary.app'
```

## Options

Here are some lists of command line arguments supported by Google Chrome:

* [A list of useful Google Chrome command line switches - gHacks Tech News](https://www.ghacks.net/2013/10/06/list-useful-google-chrome-command-line-switches/)
* [List of Chromium Command Line Switches « Peter Beverloo](http://peter.sh/experiments/chromium-command-line-switches/)

# squelch-base-theme
The base theme for Squelch IRC Client.

## Usage

This should set as the default theme in Squelch. You don't need to install this manually to use it.

If you wish to make your own theme from scratch, you should create a new SASS project that imports the SASS from this theme. [npm-sass](https://www.npmjs.com/package/npm-sass) is a good way to do this. (TODO: link to documentation on how to do theme development once that feature is complete).

## Development

If you want to fix/make changes to this style

### Setup

Clone this repo and run `npm install` to install dependencies.

Then run `npm link` in the cloned directory. Go to your local clone of Squelch and run `npm link squelch-base-theme`. Now running your local clone of Squelch should use the local clone of this repository you just made.

### Building

Build the SASS to CSS with `npm run build`.

### Live Editing

Running `npm run watch` will automatically compile the style whenever you save your changes. Squelch should automatically pick up and apply the newly compiled changes, making it easy to tweak the style without restarting Squelch.

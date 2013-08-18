# component-assets

Easily add all your scripts, styles, images and files to your `component.json` file.

## Install

    npm install -g component-assets

## Usage

    component assets images:icons/* scripts:*.js styles:*.css files:*.scss

Each argument is parsed with the format `field:pattern`. So you can set any field
you want by just listing the files as a glob pattern.

If you use no arguments:

    component assets

it will use these arguments by default:

    scripts:*.js styles:*.css files:files/* images:images/* templates:templates/*
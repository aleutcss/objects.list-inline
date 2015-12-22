# List-inline

The List-inline object simply displays a list as one horizontal row.

## Dependencies

aleutcss’ List-inline object depends on one other aleutcss module:

* [settings.defaults](https://github.com/aleutcss/settings.defaults)

If you install the List-inline object using NPM, you will get these dependencies at
the same time. If not using NPM, please be sure to install and `@import` these
dependencies in the relevant way.

## Installation

The recommended installation method is NPM, but you can install the List-inline
module via a Git Submodule, or copy and paste.

### 

### Install using npm:

    $ npm install --save-dev aleut-list-inline


Once installed, `@import` into your project in its Objects layer:

    @import "node_modules/inuit-list-inline/objects.list-inline";

### Install as a Git Submodule

    $ git submodule add git@github.com:aleutcss/objects.list-inline.git

Once installed, `@import` into your project in its Objects layer:

    @import "objects.list-inline/objects.list-inline";

### Install via file download

The least recommended option for installation is to simply download
`_objects.list-inline.scss` into your project and `@import` it into your project in
its Objects layer.

## Usage

Basic usage of the List-inline object uses the required classes:

    <ul class="o-list-inline">
        <li>Foo</li>
        <li>Bar</li>
        <li>Baz</li>
    </ul>

The only valid children of the `.o-list-inline` node are `li`s.

## Options

Other, optional classes can supplement the required base classes:

* `.o-list-inline--delimited`: add a character to delimit list items.

For example:

    <ul class="o-list-inline  o-list-inline--delimited">
        <li>Foo</li>
        <li>Bar</li>
        <li>Baz</li>
    </ul>

If you wish to completely remove the whitespace between items, omit the closing
`</li>` tag:

    <ul class="o-list-inline">
        <li>Foo
        <li>Bar
        <li>Baz
    </ul>

# vim-lelab

Transform ES5 snippets of code to ES6 using [Lebab](http://lebab.io/)

> wip

## Usage

## :Lebab

```
:Lebab %
```

Transform current buffer to ES6 with default options.

Accepts range and visual selection to perform a transform on specific code parts.

## Options

Drop a .lebabrc file in the project repository.

Additionnaly, the following locations are used to merge into .lebabrc configuration, before transforming with lebab.

- ~/.config/lebab/.lebabrc
- ~/.lebab/.lebabrc
- ~/.lebabrc

Q: rc or opts ? rc would be json, opts would be line delimited cli flags. opts simpler:

```
--enable <a,b,c>   # enable only specified transform
--disable <a,b,c>  # disable specified transform
```

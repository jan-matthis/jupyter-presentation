# Jupyter CSS for presentations

Minimal stylesheets for presentations in [Jupyter](http://jupyter.org/) Notebooks.

All cells except the contents and output of the currently active cell are hidden. Using the keybindings (arrow keys or `j` / `k` per default) cells can
be switched.


## Usage

To use, simply include and execute a cell in the notebook that loads the CSS files, e.g.:
```html
%%html
<link rel="stylesheet" href="css/cells.css">
<link rel="stylesheet" href="css/codemirror.css">
<link rel="stylesheet" href="css/jupyter.css">
<link rel="stylesheet" href="css/presenter.css">
```

Note that the file `jupyer.css` is a general stylesheet for notebooks, that
can also be used as a default. See [jupyter-css](http://github.com/jan-matthis/jupyter-css) for instructions.

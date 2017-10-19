# dotfiles

My macOS dotfiles.


## How to install

The installation step requires the [XCode Command Line
Tools](https://developer.apple.com/downloads) and may overwrite existing
dotfiles in your HOME directory.

```bash
$ bash -c "$(curl -fsSL raw.github.com/disquisition/dotfiles/master/bin/dotfiles)"
```

If you wish to fork this project and maintain your own dotfiles, you must
substitute my username for your own in the above command and the 2 variables
found at the top of the `bin/dotfiles` script.


## How to update

Run the dotfiles command:

```bash
$ dotfiles
```

Options:

<table>
    <tr>
        <td><code>-h</code>, <code>--help</code></td>
        <td>Help</td>
    </tr>
    <tr>
        <td><code>--no-packages</code></td>
        <td>Suppress package updates</td>
    </tr>
    <tr>
        <td><code>--no-sync</code></td>
        <td>Suppress pulling from the remote repository</td>
    </tr>
</table>


### Custom macOS defaults

Custom macOS settings can be applied during the `dotfiles` process. They can
also be applied independently by running the following command:

```bash
$ macosdefaults
```

## Acknowledgements

Inspiration and code was taken from many sources, including:

* [@necolas](https://github.com/necolas) (Nicolas Gallagher)
  [https://github.com/necolas/dotfiles](https://github.com/necolas/dotfiles)
* [@nicksp](https://github.com/nicksp) (Nick S. Plekhanov)
  [https://github.com/nicksp/dotfiles](https://github.com/nicksp/dotfiles)

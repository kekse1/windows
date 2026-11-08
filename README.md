<img src="without.svg" /><br>
<img src="https://kekse.biz/github.php?draw&override=github:windows" />

<br>

# The `Windows` key
This key is 'nonsense'. ...

## Using it '**the right way**'
... but I got one on my new laptop, and I like it.

The reason: any key can be kinda 'macro' key. So it can be used for any functionality.
Especially on Linux. Or because I only know how to do it on this OS (the only one I'm using)..

### The keyboard layout
I'm using [**`xfce4`**](https://www.xfce.org/) and a tiny script I wrote on my own for this
purpose. I'm from Germany, and sometimes I need to write umlauts (`ue`, `ae`, `oe`, .. and
some other special characters). But I don't want to miss the advantages of the `us` layout,
especially when I'm coding.

<br>

# The script `layout.sh`
Dependencies are:

* The [`bash` shell](https://www.gnu.org/software/bash/)
* `apt install x11-xkb-utils`

The script itself ...

* [`layout.sh`](./src/layout.sh) v**0.2.1**

<br>

## Usage
* Call it w/out any parameter to display the current keyboard layout.
* Call it with the concrete layout as parameter (e.g. `us`).
* Call it with `-` as parameter to rotate between configured layouts.

<br>

## Setup
Since I'm using the [**`xfce4`**](https://www.xfce.org/), it's very easy to setup everything.

Copy [my script](#the-script-layoutsh) to e.g. `/usr/local/bin/layout.sh`. Then go to the `xfce4`
settings (via right click on the desktop, to select `Applications`, then `Settings` and in there
the `Keyboard`, to select the tab `Shortcuts for Applications` (or smth. like this)). There you
can click on the button `Add` to type in the path of [my script](#the-script-layoutsh). Finally
you'll have to capture the key to assign it to [my script](#the-script-layoutsh). Use the `-`
parameter for rotation, otherwise use the concrete layouts as parameter when you use different keys.

## Beautify
Xfce got it's own element for the main bar. Adding this tool to the bar will let you always
see which layout is selected.

<br><br><br>

# Contact
<img src="https://kekse.biz/github.php?override=github:windows&draw&text=windows@kekse.biz&angle=6&size=38pt&fg=150,20,90&font=OpenSans&ro&readonly&h=64&v=16" />

<br>

# Copyright and License
The Copyright is [(c) Sebastian Kucharczyk](COPYRIGHT.txt),
and it's licensed under the [MIT](LICENSE.txt) (also known as 'X' or 'X11' license).

<a href="https://kekse.biz/">
<img src="favicon.png" alt="Favicon" />
</a>


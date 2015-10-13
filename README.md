# Text mate syntax highlighting

I only test these packages on Sublime Text 3.

Although there's no license on them, please let me know if you use / modify
these packages.


## Installation

For convenience the repo includes the unreadable `.tmLanguage` files so that
the [AAAPackageDev][package dev] package is not needed for installation.

Just copy these files to

```bash
<sublime text path>/Packages/User/.
```


## Modification

To modify the packages first retrieve the [AAAPackageDev][package dev] package.
Follow the installation procedure, and open the file in
```bash
<sublime text path>/Packages/User/
```
that you want to edit.
Edit it, and run *Build With: Convert to...* either using the fuzzy search menu
("Ctr+shift+p" or "command+shift+p") or by clicking on *Tools*, *Build With...*
and then *Convert to ...*.

In general you should not need to restart Sublime Text, but sometimes when the
build fails it's necessary.


[package dev]: https://packagecontrol.io/packages/AAAPackageDev (Sublime Text 3 dev package)
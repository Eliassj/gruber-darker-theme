[![MELPA](http://melpa.org/packages/gruber-darker-theme-badge.svg)](http://melpa.org/#/gruber-darker-theme)
[![MELPA Stable](http://stable.melpa.org/packages/gruber-darker-theme-badge.svg)](http://stable.melpa.org/#/gruber-darker-theme)

# Gruber Darker #

[Gruber Darker](http://jblevins.org/projects/emacs-color-themes/color-theme-gruber-darker.el.html)
color theme for Emacs by Jason Blevins. A darker variant of the
[Gruber Dark](http://daringfireball.net/projects/bbcolors/schemes/)
theme for BBEdit by John Gruber. Adapted for deftheme and extended by
Alexey Kutepov a.k.a. rexim.

# Screenshot #

![gruber-darker-theme](http://i.imgur.com/8dY71hX.png)

# Installation #

## Manual old fashioned way ##

Download the theme to your local directory. You can do it through `git
clone` command:

```
git clone git://github.com/rexim/gruber-darker-theme.git
```

Then add path to gruber-darker-theme to custom-theme-load-path list —
add the following to your emacs config file somewhere (.emacs,
init.el, whatever):

```
(add-to-list 'custom-theme-load-path
             "/path/to/gruber-darker-theme/")
```

Use `M-x customize-themes` to change your current theme.

# Contribution #

Gruber Darker is an awesome theme. But it has a lack of support for
many good modes. I add color faces only for modes I use. If you like
this theme and use a mode that looks very bad with it, feel free to
add appropriate color faces (see file gruber-darker-theme.el) and send
me a pull request.

Thanks.

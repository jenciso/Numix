# My Numix Theme

## Installation

```shell
mkdir -p ~/.themes && cd ~/.themes
git clone https://github.com/jenciso/Numix.git
git checkout custom-dark
```

## Customize your theme

Extract the css file

```shell
cd gtk-3.20/
gresource list gtk.gresource
gresource extract gtk.gresource  /org/numixproject/gtk-3.20/dist/gtk-dark.css > gtk.css
```

Edit `gtk.css` file to customize the theme

## References

- https://askubuntu.com/questions/1261156/editing-yaru-gtk-theme-where-is-resource-com-ubuntu-themes-yaru-3-20-gtk-css
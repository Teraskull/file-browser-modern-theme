<h1 align="center">
  Modern
</h1>
<p align="center">
    Alternative dark theme for https://github.com/filebrowser/filebrowser/
</p>

<div align="center">

  ![Main window](https://user-images.githubusercontent.com/24798198/146664480-bdd54ca0-e6c2-4cba-ba51-dab0b8f7a28d.png)

  ![Settings](https://user-images.githubusercontent.com/24798198/146664515-f22e34a1-aadb-4820-93c8-c0e57dcac632.png)

</div>


# Usage

## Local:
Copy the contents of [`custom.css`](/custom.css) or [`custom.min.css`](/custom.min.css) to your own `custom.css` file.

You can read about the File-Browser `custom.css` customization [here](https://filebrowser.org/configuration/custom-branding).

## CDN:
Add the following to your `custom.css` file:
```css
@import url("https://cdn.jsdelivr.net/gh/Teraskull/file-browser-modern-theme@master/custom.min.css");
```

# Customizing

## Icons
Because the icon replacements rely on `aria-label`, most of the new icons are only visible when English language is selected.

To use the default icons, remove the styles between the following comments at the end of [`custom.css`](/custom.css):
```css
/* ############### ICON THEME ############### */

/* ############### END ICON THEME ############### */
```

## Editor theme
1. Copy the contents of any CSS theme from https://github.com/ajaxorg/ace/blob/master/lib/ace/theme/.
2. Replace all instances of the theme class name with `.ace-twilight`.
> For example, if you copy the `nord-dark` theme, replace all `.ace-nord-dark` classes with `.ace-twilight`.
3. Paste the replaced contents between the following comments:
```css
/* ############### EDITOR THEME ############### */

/* ############### END EDITOR THEME ############### */
```


## License

Distributed under the AGPL-3.0 License. See [`LICENSE`](/LICENSE) for more information.

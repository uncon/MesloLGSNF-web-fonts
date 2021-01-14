# MesloLGS NF Web Fonts

This is simply the Meslo Nerd Font (MesloLGS NF) patched for [Powerlevel10k](https://github.com/romkatv/powerlevel10k) in woff2 format for use on Chrome OS.

## Usage

### [Secure Shell App](https://chrome.google.com/webstore/detail/secure-shell/pnhechapfaindjhompbnflcldabbghjo)

* Launch *Secure Shell App*, and click on **Options**
	* **Text font family**: `"MesloLGS NF", monospace`
	* **Custom CSS (URI)**: `https://www.uncon.net/MesloLGSNF-web-fonts/stylesheet.css`

### Linux Terminal or [Crosh Window](https://chrome.google.com/webstore/detail/crosh-window/nhbmpbdladcchdhkemlojfjdknjadhmh)

* Launch Terminal, press `ctrl+shift+j`, and paste the following:

```js
term_.prefs_.set('font-family', '"MesloLGS NF", monospace');
term_.prefs_.set('user-css', 'https://www.uncon.net/MesloLGSNF-web-fonts/stylesheet.css');
```

# MesloLGS NF Web Fonts

## Usage

### [Secure Shell App](https://chrome.google.com/webstore/detail/secure-shell/pnhechapfaindjhompbnflcldabbghjo)

* Launch *Secure Shell* and click on **Options**
  (or go to `chrome-extension://pnhechapfaindjhompbnflcldabbghjo/html/nassh_preferences_editor.html`):
	* Set **Text font family**: `"MesloLGS NF", monospace`
	* Set **Custom CSS (URI)**: `https://www.uncon.net/MesloLGSNF-web-fonts/stylesheet.css`

### [Crosh Window](https://chrome.google.com/webstore/detail/crosh-window/nhbmpbdladcchdhkemlojfjdknjadhmh)

* Start crosh window then press `Ctrl+Shift+J` and paste in the following:

```js
term_.prefs_.set('font-family', '"MesloLGS NF", monospace');
term_.prefs_.set('user-css', 'https://www.uncon.net/MesloLGSNF-web-fonts/stylesheet.css');
```

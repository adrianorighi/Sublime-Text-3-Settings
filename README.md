# Sublime Text 3 Settings
My personal settings for Sublime Text 3.

To use: Preferences > Settings - User.
Paste the file content.

## Plugins - Packages
First install the Package Control. For this, paste the code in the Console (Ctrl + ` or View > Show Console).

import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)

Press Ctrl + Shift + P and select Package: Install. Search the desired package.

## My Instaled Packages
1. SublimeLinter
2. PHP Code Sniffer
3. JsFormat
4. DocBlock
5. SublimeHighlight
6. Emmet
7. jQuery
8. Sublimerge
9. AlignTab
10. CSS3
11. Git
12. Git Conflict Resolver
13. Laravel 5 Artisan
14. PHP Companion
15. Trainling Spaces
16. XDebug
17. Gulp
18. Sublime CodeIntel

## My Installed Theme
Material Theme
https://github.com/equinusocio/material-theme

### How to install the theme
1. Download the lastest release from https://github.com/equinusocio/material-theme.
2. Extract and rename the folder to "Material Theme".
3. Move the "Material Theme" folder to ~./.Sublime-Text-3/Packages/


www.adrianorighi.com

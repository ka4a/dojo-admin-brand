Dojo Admin Brand
======

This project contains the default branding assets and style used in Open edX applications. 
It is published on npm as @reustleco/dojo-admin-brand.

How to use this package
----

1. Install the package
   
```angular2html
npm install --save @reustleco/dojo-admin-brand@npm:@reustleco/dojo-admin-brand
```

2. Make sure that `/logo.svg`, `/logo-trademark.svg`, `/logo-white.svg` and `/favicon.ico`
are existed in the brand package and match filenames exactly, because Open edX applications refer 
   to these files by their filepath.


Usage
----
Import assets from this package in an application:
```angular2html
import logo from '@reustleco/dojo-admin-brand/logo.svg';
```



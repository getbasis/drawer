# getbasis-drawer
This is a css module for the Basis.

## Basis
* Repository: https://github.com/getbasis/basis/
* Documents : http://getbasis.github.io/

## Get Started

### Install
```
$ npm install getbasis
$ npm install getbasis-drawer
```

### Stylus
```
@import 'node_modules/getbasis-drawer/src/stylus/basis';
@import 'node_modules/getbasis-drawer/src/stylus/object/component/drawer';
```

### Javascript
```
import $ from 'jquery';
import BasisDrawer from 'node_modules/getbasis-drawer/src/js/drawer.js';
```

### HTML
[data-bs-component="drawer__body"] must be right under [data-bs-component="drawer"]

```
<body data-bs-component="drawer">
  <nav id="drawer" data-bs-component="drawer__body" role="navigation" aria-hidden="true">
    <ul data-bs-component="drawer__menu">
      <li data-bs-component="drawer__item"><a href="#">menu</a></li>
      <li data-bs-component="drawer__item"><a href="#">menu</a></li>
      <li data-bs-component="drawer__item">
        <a href="#">menu</a>
        <div data-bs-component="drawer__toggle" aria-expanded="false" aria-controls="drawer-submenu">&gt;</div>
        <ul id="drawer-submenu" data-bs-component="drawer__submenu" aria-hidden="true">
          <li data-bs-component="drawer__subitem"><a href="#">submenu</a></li>
          <li data-bs-component="drawer__subitem"><a href="#">submenu</a></li>
        </ul>
      </li>
    </ul>
  </nav>
  <div class="_c-hamburger-btn" data-bs-component="drawer-btn" aria-expanded="false" aria-controls="drawer"></div>
</body>
```

## Browser support
Modern Browser and IE10+

## License
MIT License

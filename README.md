# amdocs-workshops

- https://github.com/alonronin/amdocs-react-bootstrap
- https://github.com/alonronin/amdocs-components
- https://github.com/alonronin/amdocs-responsive-form
- https://github.com/alonronin/amdocs-mobx-router
- https://github.com/alonronin/amdocs-webpack-workshop

### Flex

- https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties
- https://codepen.io/justd/pen/yydezN/
- http://jsbin.com/boritagapi/5/edit?css,output

### E2E

- https://www.testim.io/
- https://applitools.com/
- https://www.cypress.io/ (open source)

### Webstorm Plugins

- https://quokkajs.com/

### Micro Front-End presentation

- https://docs.google.com/presentation/d/1LywSnZjWt_hrHKVVPCSq4GCxulxOZJ_5cSX-4_ww9p4/edit?usp=sharing

### Wrapping bootstrap with css modules and scss

```scss

.bootstrap {
  :global {
    @import "~bootstrap/scss/bootstrap"
  }
}

```

```js
import { bootstrap } from './style.scss';

function Component() {
  return <div className={bootstrap}>// ... your bootstrap markup </div>;
}
```

### Useful Links

- [Great React Boilerplate with Canonical Routing](https://github.com/kriasoft/react-static-boilerplate)
- [JS Best Practices](https://github.com/mbeaudru/modern-js-cheatsheet)
- [Great books on JS and ES-NEXT](http://exploringjs.com/)
- [MobX Video on egghead.io](https://egghead.io/lessons/javascript-derive-computed-values-and-manage-side-effects-with-mobx-reactions)


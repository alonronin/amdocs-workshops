# amdocs-workshops

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

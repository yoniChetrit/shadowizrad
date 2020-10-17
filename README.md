# What is this?

Get perfect shadows every time for the non-designer;

# installation

`npm i shadowizard --save `

Then...

```
import { shadowizard } from 'shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
});
```

## Options

Shadowizard supports 2 options, both of which are optional:

* *shadow_type* _hard | soft_ (Defualts to soft)
* *padding* - _boolean_ (defualt to false)
# What is this ?

Perfect shadow creation for non-designers. Works well with pictures.

# Installation

`npm i shadowwiz --save`

Then...
```
import { shadowWiz } from 'shadowwiz';

shadowWiz({
    shadow_type: 'soft',
    padding: false
});
```


## Options

ShadowWiz supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)
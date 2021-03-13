# Installation

` npm i testPlugin --save `

Then...

```
import { testPluign } from 'testPlugin';

testPlugin({
    shadow_type: 'soft',
    padding: false
});
,,,


## Options

There are 2 options:

* *shadow_type* - _hard / soft_ (Deafult to soft)
* *padding* - _boolean_ (Default to false)
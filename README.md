# Misleading Node error

Try to figure out why Node complains

```
import { foo } from '../lib/index.js';
         ^^^
SyntaxError: The requested module '../lib/index.js' does not provide an export named 'foo'
```

...when clearly [`lib/index.js`](lib/index.js) *does* export `foo`.

Done? Congratulations! Now imagine how much harder the puzzle is with real-world files, in particular large `package.json`s.

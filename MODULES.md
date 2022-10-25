# Modules

## step 1

script type="module" src=""

## step 2

`export something`

//modules.js

```
export function sayHi() {
  console.log("hi");
}

export const people = ["Peter", "Jonas"];
```

//default.js

```
const name = "Jonas";
export default name;

```

## Step 3

`import something`

//index.js

```
import { sayHi, people } from "./modules.js";
import name from "./default.js"
sayHi();


```

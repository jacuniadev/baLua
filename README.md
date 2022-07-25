# baLua
JavaScript-like syntax for Lua

# Variables
```js
const vv = 3;
vv = 4;
```
Error will be thrown

# Math operators
```js
let test = 3;
test++;
test--;
test += 5;
test /= 4;
test *= 3;
test ^= 2;
test -= 1;
```

# Loops
```js
let test = [5, 6, 7];
for(c in test) {
  print(c);
}
// 1, 2, 3

for(c of test) {
  print(c);
}
// 5, 6, 7

for(k,v in test) { // OR of
  print(k, v);
}
```

# Arrow functions
```js
let test = () => {
  print("hello, world!");
}
test(); // hello, world!

let test = (a, b) => a + b;
print(test(1, 2)); // 3
```

# Try and catch
```js
try {
  nonExistingFunction();
} catch {
  print("can't call this function!");
}

try {
  nonExistingFunction();
} catch(e) {
  print("error: " .. e);
}
```

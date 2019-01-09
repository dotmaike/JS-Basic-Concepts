# JS Basic Concepts

These are some basic concepts in Javascript that we sometimes take for granted.

## 1. Call Stack

**Javascript Concurrency Model (implemented inside of [**Google V8**](https://developers.google.com/v8/) and [**SpiderMonkey**](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey)).**

> It’s a **LIFO — Last In, First Out** data structure which records the function calls, basically where in the program we are.

**Heap** : All the memory allocation to variables and objects happens here.

There is a limit on the size of the stack which is 16,000 frames (Chrome browser).

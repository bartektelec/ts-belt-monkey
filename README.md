# ts-belt-monkey
A library that converts basic JavaScript APIs to follow a more functional approach that fits ts-belt.
Eliminate code smells of JavaScript like NaN, Invalid Date and undefineds*

## Todos:
- [ ] Option instead of NaN from Number constructor, parseInt and parseFloat
- [ ] Result from JSON.stringify and JSON.parse
- [ ] Result from Promise rejection
- [ ] Add global Option and Result to the global scope
- [ ] Option instead of Invalid Date for Date constructor
- [ ] Investigate fixing enums, if they can exist in the runtime and hold additional data
- [ ] Investigate pattern matching*
- [ ] Optional monkeypatching of regular primitive and object methods i.e make array.find return an Option
- [ ] Fetch to use bind/map/flatMap syntax like ts-belt
- [ ] Investigate structs that live in the runtime and allow constructing and runtime type checking and additional methods
- [ ] Investigate traits that can be applied to structs
- [ ] Investigate runtime types
- [ ] Investigate branded types

[*] - Dont even know if it's fucking possible

parseInt(wolfMan) = +wolfMan
 make it into an object and then export it!!!!
 Global constants are supposed to be in ALL capital letters!!!


 !!0 = false // Real false not falsey

 const testWolf = 0 || 'wolfMan'
 The reverse of short-circuit operator
  let testWolf = 1 && 'wolfMan'


iterable and enumerable
Iterables = index in Arrays
enumerable = key in Objet


objects are not iterable

for .. of for [array, Map, Set, String] to iterate over values;
for of give u values
for of loop   iterates over an array
for of  Arrays // returns the value
for of  strings // returns the value
---------------------
for in give u the key
The for...in loop iterates over the enumerable properties of an object. It also goes up to the prototype chain and enumerates over inherited properties.
  for in Objects // returns the key
  for in  Arrays // returns the key
   for in  strings // returns the key


A mnemonic:

'o'f -> not 'o'bjects;
'i'n -> not 'i'terables.
Another mnemonic:

for..in..keys === foreign keys === use for...in for keys;
for...of for values.
in gives you index.


 Object.defineProperty(Object.prototype, 'dirWolf', {
        value: (param1) => {
          console.dir(param1);
        },
        enumerable: false,
        configurable: false,
        writable: false
      });


      if (done) return;


Import Lodash
    <script type="module" src="https://cdn.jsdelivr.net/npm/lodash@4.17.21/lodash.min.js" defer></script>


______________________
const union = Array.from(new Set([...threeArray, ...fiveArray]));
  const result = union.reduce((sum, a) => sum + a, 0);
  ---------------------------

Practice Array.reduce()
Practice Array.filter()

<!-- Ternary  arrow function -->
const WOLF = 'wolfMan' || (() => 0)();
const FALSE = false;
const TESTMICH = FALSE || (WOLF && (() => 'kim22')());
console.log(`TESTMICH: ${TESTMICH}`);

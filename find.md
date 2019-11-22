# .find

1. What does `.find` do?
  \n finds the first item that matches condition in array
2. Is the original array modified?
  \n not modified
3. How many arguments does `.find` take?
  \n one a callback function
4. How many arguments does the _callback function_ take?
  \n one the array to search on
5. Which arguments are required (for both the method and its callback)?
  \n both
6. Does the callback need a return value? If so, what needs to be returned?
  \n a boolean must returned 

## Example 1:
Given an array of countries, write a function that returns the first listed country in North America

Ex:

```javascript
var countries = [
  {
      "countryCode": "AS",
      "countryName": "American Samoa",
      "population": "57881",
      "capital": "Pago Pago",
      "continentName": "Oceania"
  },
  {
    "countryCode": "AI",
    "countryName": "Anguilla",
    "population": "13254",
    "capital": "The Valley",
    "continentName": "North America"
  },
  {
      "countryCode": "AD",
      "countryName": "Andorra",
      "population": "84000",
      "capital": "Andorra la Vella",
      "continentName": "Europe"
  },
  {
      "countryCode": "AO",
      "countryName": "Angola",
      "population": "13068161",
      "capital": "Luanda",
      "continentName": "Africa"
  },
  {
      "countryCode": "SX",
      "countryName": "Sint Maarten",
      "population": "37429",
      "capital": "Philipsburg",
      "continentName": "North America"
  },
];

findFirstNorthAmericanCountry(countries) // => {
//     "countryCode": "AI",
//     "countryName": "Anguilla",
//     "population": "13254",
//     "capital": "The Valley",
//     "continentName": "North America"
// }

```
## Example 2:

Given the previous array of countries, find the first country with a capital that has a three-word name

```js
findThreeNameCapital(countries) // => {
//   "countryCode": "AD",
//   "countryName": "Andorra",
//   "population": "84000",
//   "capital": "Andorra la Vella",
//   "continentName": "Europe"
// }
```

# .map

1. What does `.map` do?
  \n creates an array of the same length based on restructure function
2. Is the original array modified?
  \n no
3. How many arguments does `.map` take?
  \n one
4. How many arguments does the _callback function_ take?
  \n none
5. Which arguments are required (for both the method and its callback)?
  \n yes an index
6. Does the callback need a return value? If so, what needs to be returned?
  \n it can take one

## Example 1:

Given a list of countries, write a function that returns an array of strings with the country code and name

Ex:
```javascript

var countries = [
  {
    "countryCode": "AF",
    "countryName": "Afghanistan",
    "population": "29121286",
    "capital": "Kabul",
    "continentName": "Asia"
  },
  {
    "countryCode": "AL",
    "countryName": "Albania",
    "population": "2986952",
    "capital": "Tirana",
    "continentName": "Europe"
  },
  {
    "countryCode": "DZ",
    "countryName": "Algeria",
    "population": "34586184",
    "capital": "Algiers",
    "continentName": "Africa"
  },
]

explainCodes(countries) // => ["AF stands for Afghanistan","AL stands for Albania","DZ stands for Algeria"]
```

## Example 2:
Write a function that takes the same list of countries, and returns an array of objects with just countryNames, capitals and continentNames.

```js
cleanCountryData(countries)
/*
returns:
[
  {
    "countryName": "Afghanistan",
    "capital": "Kabul",
    "continentName": "Asia"
  },
  {
    "countryName": "Albania",
    "capital": "Tirana",
    "continentName": "Europe"
  },
  {
    "countryName": "Algeria",
    "capital": "Algiers",
    "continentName": "Africa"
  },
]
*/

```

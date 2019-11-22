# .forEach

1. What does `forEach` do?
  \n loops through each item of an array
2. Is the original array modified?
  \n no
3. How many arguments does `forEach` take?
  \n up to three
4. How many arguments does the _callback function_ take?
  \n one the index
5. Which arguments are required (for both the method and its callback)?
  \n 
6. Does the callback need a return value?
  \n 

Given a list of countries, write a function that returns an array of all the country codes using `.forEach`.

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

getCodes(countries) // => ["AF","AL","DZ"]

```

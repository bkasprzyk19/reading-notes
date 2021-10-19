[<==Back](README.md)

## Describe (in plain English) what Array.map() does

- mapping an array runs a function on each element to return a new array with the same length

## Describe (in plain English) what Array.reduce() does

- this runs the callback function on each element once, the return value is the accumulation of all the values such as a sum

## Provide code snippets showing how to use superagent() to fetch data from a URL and log the result

## With normal Promise .then() syntax

``` javascript
const superagent = require('superagent');

function getCharacters() {
  superagent.get('https://swapi.dev/api/people/70')
  .then(data => {
    console.log({
        [data.body.name] : data.body.url
      });
  })
  .catch(err => {
    console.error(err);
    })
}
getCharacters();

```


## Again with async / await syntax

``` javascript
const superagent = require('superagent`);

async function getCityInfo(city) {
  try {
    let cityResults = await superagent.get(`https://geocode.xyz/${city}?json=1`);
    // console.log(cityResults.body);
    console.log(`The latitude and longitude for ${city} is: ${cityResults.body.latt} and ${cityResults.body.longt}, respectively.`)
  } catch(error) {
    console.log('error from inside getCityInfo')
  }
}
getCityInfo('seattle');
```

## Explain promises as though you were mentoring a Code 301 level student

It basically tells us that we are going to clear it from the stack but once the code is done running we will get the return value, this just opens up the stack ?

## Are all callback functions considered to be Asynchronous? Why or Why Not?

not by default, it is passed as an argument until it is executed.
# Notes 1

## Array.map():

Array.map() is an array method that "maps" or examines the items of an array and creates a new array with the inputs of the first array replaced by whatever value is given in the .map() method.

## Array.reduce():

The Array.reduce() method examines an arrays values and turns the array into a single element.

## Code Snippet of superagent():

superagent.get('someurl.com/data')
  .then(
    console.log(value)
  )

  async () => {
    try {
    const res = await superagent.get('someurl.com/data');
    console.log(res);
    } catch (err) {
    console.error(err);
    }
  }

A promise is just a Javascript call that your code will wait to return before continuing down the call stack.

NO! Just because a function is using a Callback does not mean that it is necessarily asynchronous.


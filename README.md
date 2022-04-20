# Food-API

This is a mock REST API with different types of food.

To view the live API, visit [here](https://gunter-food-api.herokuapp.com/).

The API supports any type of HTTP request and can even return a single item from an endpoint. For example, to get the pizza having the Id of 0:

```js
fetch('https://gunter-food-api.herokuapp.com/pizza/0')
    .then((response) => response.json())
    .then((data) => console.log(data))
```

## Credits

This API has been created with the help of [Ania Kubów's tutorial](https://www.youtube.com/watch?v=FLnxgSZ0DG4).

## Contributing

Feel free to make a pull request and add more items in the database, following the same format in [db.json](./db.json) (you can add other fields too).

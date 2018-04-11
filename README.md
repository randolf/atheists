# Atheist quotes API
Because I'm an atheist, and this is a very simple Node server.

## Production host
[https://atheists.herokuapp.com/v1/quotes](https://atheists.herokuapp.com/v1/quotes)

The `Access-Control-Allow-Origin` header is set to `*` so that you can make requests from any domain.

## APIs

### `GET /v1/quotes`
Returns an array containing one quotation:
```
[
	"The way to see by faith is to shut the eye of reason - Benjamin Franklin"
]
```

### `GET /v1/quotes/<count>`
Returns an array containing `<count>` quotations (e.g., `GET /quotes/2`)
```
[
	"The way to see by faith is to shut the eye of reason. -- Benjamin Franklin",
	"I'd take the awe of understanding over the awe of ignorance any day. -- Douglas Adams"
]
```

### To-do items

  - add more quotations
  - spread the knowledge

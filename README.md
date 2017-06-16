# bs-cookie-parser
[cookie-parser](https://github.com/expressjs/cookie-parser) binding in ReasonML

# Example

```Javascript
let app = Express.express ();

App.use app (CookieParser.make ()); 

App.listen app port::3000 ;
```

# Installation 

> use npm package bs-cookie-parser

# Testing in development

In one terminal:
```
npm run start
```

In second terminal:
```
cd tests && ./test.sh
```

> Testing relies on querying a the `example/Index.re` server and making sure the output matches the `tests/reference.data`.

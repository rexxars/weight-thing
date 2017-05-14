* RabbitMQ
* Docker
* Rate limit
* Central DB
* REST/GraphQL API
* Determine what to browserify? Browser field used?
* Webpack instead of browserify? Modules field etc?

Can we get a smaller document? Just need the name, I think. Mayhaps version.

```js
var changes = new ChangesStream({
  db: 'https://skimdb.npmjs.com/registry',
  include_docs: true,
  since: 'now'
})

changes.on('data', function (change) {
  var name = change.doc.name
})
```

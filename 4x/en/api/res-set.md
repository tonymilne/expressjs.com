Set header `field` to `value`, or pass an object to set multiple fields at once.

```js
res.set('Content-Type', 'text/plain');

res.set({
  'Content-Type': 'text/plain',
  'Content-Length': '123',
  'ETag': '12345'
})
```
js
Aliased as `res.header(field, [value])`.

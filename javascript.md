### Declaration

Not

```js
var a = 0,
    b = 'stuff';
```

Not

```js
var a = 0
  , b = 'stuff';
```

Use

```js
var a = 0;
var b = 'stuff';
```

Reason

* debugging
* modification

## Naming

jQuery node

Not

```js
var div = $('.somediv');
```

Use

```js
var $div = $('.somediv');
```

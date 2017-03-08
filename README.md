doc-indexer
===========

built for static page full-text search

![structure](./assets/structure.png)

## install

```shell
$ npm i doc-indexer --save
```

## DocSet

html, markdown, etc.

## tokens

```javascript
{
    docs: {
        a: 'uri/to/a-file',
        b: 'uri/to/b-file',
    },
    tokens: {
        'someToken': {
            stem: 'someToken',
            minSize: 8,
            maxSize: 9,
            count: 10,
            indices: [
                {
                    ranking: 0,
                    link: '#xxx',
                    doc: 'a',
                    index: 0
                }
            ]
        }
    }
}
```

## use in terminal

TODO

## use in browser

TODO


# 1.0.0 Meta File Specifications

The file must be named `meta.json` and be placed within the library item's directory.

## meta.json

```json
{
    "_infover": "1.0.0",
    "title": "Lorem Ipsum",
    "author": "John Doe",
    "date": "1990-01-01",
    "content": "LoremIpsum.txt",
    "flags": ["text", "prose", "example", "libalexandria"],
    "description": "An empty LibAlexandria Item."
}
```

* `_infover`: Version code of the meta file.
* `title`: Title of the associated written piece.
* `author`: The name of the author or authors of the associated written piece.
* `date`: The date of creation for the associated written piece in the `YYYY-MM-DD` format.
* `content`: A local, relative, filepath to the associated written piece.
* `flags`: An array of string tags for the associated written piece.
* `description`: A description of the content within the associated written piece.

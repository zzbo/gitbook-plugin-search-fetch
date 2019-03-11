# gitbook-plugin-search-fetch

A powerful search plugin for GitBook.

### Features

    * Allows you to pull search results from a remote server.
    * Support jsonp data type.

### Use this plugin

 Before use this plugin, you should disable the default search plugin first, 
 Here is a `book.json` configuration example:

```
{
    plugins: ["-lunr", "-search", "search-fetch"]
}
```

> Note: Only gitbook >= 3.0.0 support

* [gitbook-plugin-lunr](https://github.com/GitbookIO/plugin-lunr)
* [gitbook-plugin-search](https://github.com/GitbookIO/plugin-search)
* [gitbook-plugin-search-plus](https://github.com/lwdgit/gitbook-plugin-search-plus)
* [mark.js](https://github.com/julmot/mark.js)

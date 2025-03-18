# Notion Random Quote

This is a widget for [Notion](https://notion.so). You can use the save the code on your repo and follow [embed item instructions](https://www.notion.so/help/embed-and-connect-other-apps) to have it on your notion templates.

## Add a different source

You can add a different source for random quotes. This source must be a JSON file hosted somewhere.

The valid JSON file must be in this format: `notion-quote.json`

```json
[
  {
    "author": "First Author Name",
    "content": "First Quote Content."
  },
  {
    "author": "Second Author Name",
    "content": "Second Quote Content."
  }
]

```

You have to add the url of your JSON file with parameter `f` into query parameters.
If you're using a gist, make sure you use the raw version.

Here is an example for [my gist](https://gist.github.com/</user>/<ID>):

```url
https://example/notion-quote/?f=https://gist.githubusercontent.com/saman/a4326228c01f7fe15de6707655352300/raw/6ae8c92baae70fb842ddf91f3465ccab5f7b1622/notion-quote.json
```

Minimal template for JSDoc 3
---
A minimal template for creating clean documentation for one-namespace libraries.

See a [demo](https://rawgit.com/chiedolabs/objob/master/docs/ob.html).

Currently, I need to fix a bug where index.html is blank. For now, you will need to visit YOURNAMESPACE.html for your documentation.

Usage
---

```
npm install --save-dev minimal-jsdoc
```

```
$ jsdoc -t .node_modules/minimal-jsdoc -c `configuration file` `source files` `README.md file`
```

conf.json
---
You can set options for customizing your documentations.

```
"templates": {
	"version": "1.0.0",
    "applicationName": "Demo",
    "disqus": "",
    "googleAnalytics": "",
    "openGraph": {
        "title": "",
        "type": "website",
        "image": "",
        "site_name": "",
        "url": ""
    },
    "meta": {
        "title": "",
        "description": "",
        "keyword": ""
    },
    "linenums": true
}
```

License
---
This project under the MIT License. and this project refered by default template for JSDoc 3.


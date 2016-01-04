Minimal template for JSDoc 3
---
A minimal template for creating clean documentation for one-namespace libraries.

See a [demo](https://rawgit.com/chiedolabs/objob/master/docs/ob.html).

You will need to link to your namespace file from the index yourself by passing a README to jsdoc.

This is still a beta and hasn't been heavily field tested.

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

Credits
---
Many credits go to davidshimjs as this is a fork of [davidshimjs/jaguarjs-jsdoc](https://github.com/davidshimjs/jaguarjs-jsdoc)

License
---
This project under the MIT License. and this project refered by default template for JSDoc 3.


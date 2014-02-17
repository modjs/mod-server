mod-server
===

Development server.

## Features

* Live browser reloads, instantly see changes in your browser
* Remote logging for mobile development
* Web debugging proxy
* Deploy sever

## Usage

```js
module.exports = {
    plugins: {
        server: "mod-server"
    },
    tasks: {
        server: {
            port: 8888
        }
    }
}
```
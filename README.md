fis-receiver
========

FIS receiver on node.js

### use

```bash
$ npm install -g fis-receiver
$ fisrcv # default port 8999, use `fisrcv <port>` change port
```

_fis-conf.js_

```javascript
fis.config.merge({
    deploy: {
        remote: {
            receiver: 'http://<host>:8999/receiver',
            from: '/template',
            //远端目录
            to: '/home/template/'
        }
    }
});
```

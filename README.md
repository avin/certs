# Certificates for localhost development

## Install

```js
npm install localhost-certs
```

Install `rootCA.crt` or `rootCA.pem` in trusted root certificates 

Password for root cert: `12345678`

## Example of usage

Configure your web dev-server
```js
https = {
  key: fs.readFileSync('./node-modules/localhost-certs/files/server.key', 'utf8'),
  cert: fs.readFileSync('./node-modules/localhost-certs/files/server.crt', 'utf8'),
};
```

## More

* [vite-plugin-localhost-certs](https://github.com/avin/vite-plugin-localhost-certs)

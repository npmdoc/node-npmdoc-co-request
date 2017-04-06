# api documentation for  [co-request (v1.0.0)](https://github.com/leukhin/co-request#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-co-request.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-co-request) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-co-request.svg)](https://travis-ci.org/npmdoc/node-npmdoc-co-request)
#### co-request promisify wrapper for request

[![NPM](https://nodei.co/npm/co-request.png?downloads=true)](https://www.npmjs.com/package/co-request)

[![apidoc](https://npmdoc.github.io/node-npmdoc-co-request/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-co-request_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-co-request/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-co-request/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-co-request/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dennis Leukhin",
        "email": "dennis.leukhin@gmail.com",
        "url": "leukhin.org"
    },
    "bugs": {
        "url": "https://github.com/leukhin/co-request/issues"
    },
    "dependencies": {
        "request": "*"
    },
    "description": "co-request promisify wrapper for request",
    "devDependencies": {
        "chai": "~1.8.1",
        "co": "~3.0.2",
        "mocha": "~1.16.2",
        "nock": "~0.27.1"
    },
    "directories": {},
    "dist": {
        "shasum": "8eb5fb656c2ee1e82e36c4ccfe9376846406b260",
        "tarball": "https://registry.npmjs.org/co-request/-/co-request-1.0.0.tgz"
    },
    "gitHead": "f53f2a963b674a2876d4377122cabed427497ce9",
    "homepage": "https://github.com/leukhin/co-request#readme",
    "keywords": [
        "request",
        "rest",
        "koa",
        "co",
        "generators"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/leukhin/co-request/raw/master/LICENSE"
        }
    ],
    "main": "./",
    "maintainers": [
        {
            "name": "leukhin",
            "email": "dennis.leukhin@gmail.com"
        }
    ],
    "name": "co-request",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/leukhin/co-request.git"
    },
    "scripts": {
        "test": "mocha --harmony test/test.js"
    },
    "version": "1.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module co-request](#apidoc.module.co-request)
1.  [function <span class="apidocSignatureSpan">co-request.</span>Request (options)](#apidoc.element.co-request.Request)
1.  [function <span class="apidocSignatureSpan">co-request.</span>cookie (str)](#apidoc.element.co-request.cookie)
1.  [function <span class="apidocSignatureSpan">co-request.</span>defaults ()](#apidoc.element.co-request.defaults)
1.  [function <span class="apidocSignatureSpan">co-request.</span>del ()](#apidoc.element.co-request.del)
1.  [function <span class="apidocSignatureSpan">co-request.</span>forever ()](#apidoc.element.co-request.forever)
1.  [function <span class="apidocSignatureSpan">co-request.</span>get ()](#apidoc.element.co-request.get)
1.  [function <span class="apidocSignatureSpan">co-request.</span>head ()](#apidoc.element.co-request.head)
1.  [function <span class="apidocSignatureSpan">co-request.</span>jar (store)](#apidoc.element.co-request.jar)
1.  [function <span class="apidocSignatureSpan">co-request.</span>patch ()](#apidoc.element.co-request.patch)
1.  [function <span class="apidocSignatureSpan">co-request.</span>post ()](#apidoc.element.co-request.post)
1.  [function <span class="apidocSignatureSpan">co-request.</span>put ()](#apidoc.element.co-request.put)
1.  object <span class="apidocSignatureSpan">co-request.</span>Request.prototype

#### [module co-request.Request](#apidoc.module.co-request.Request)
1.  [function <span class="apidocSignatureSpan">co-request.</span>Request (options)](#apidoc.element.co-request.Request.Request)
1.  [function <span class="apidocSignatureSpan">co-request.Request.</span>super_ ()](#apidoc.element.co-request.Request.super_)
1.  object <span class="apidocSignatureSpan">co-request.Request.</span>defaultProxyHeaderExclusiveList
1.  object <span class="apidocSignatureSpan">co-request.Request.</span>defaultProxyHeaderWhiteList

#### [module co-request.Request.prototype](#apidoc.module.co-request.Request.prototype)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>abort ()](#apidoc.element.co-request.Request.prototype.abort)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>auth (user, pass, sendImmediately, bearer)](#apidoc.element.co-request.Request.prototype.auth)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>aws (opts, now)](#apidoc.element.co-request.Request.prototype.aws)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>debug ()](#apidoc.element.co-request.Request.prototype.debug)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>destroy ()](#apidoc.element.co-request.Request.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>enableUnixSocket ()](#apidoc.element.co-request.Request.prototype.enableUnixSocket)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>end (chunk)](#apidoc.element.co-request.Request.prototype.end)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>form (form)](#apidoc.element.co-request.Request.prototype.form)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>getHeader (name, headers)](#apidoc.element.co-request.Request.prototype.getHeader)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>getNewAgent ()](#apidoc.element.co-request.Request.prototype.getNewAgent)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>hawk (opts)](#apidoc.element.co-request.Request.prototype.hawk)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>httpSignature (opts)](#apidoc.element.co-request.Request.prototype.httpSignature)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>init (options)](#apidoc.element.co-request.Request.prototype.init)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>jar (jar)](#apidoc.element.co-request.Request.prototype.jar)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>json (val)](#apidoc.element.co-request.Request.prototype.json)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>multipart (multipart)](#apidoc.element.co-request.Request.prototype.multipart)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>oauth (_oauth)](#apidoc.element.co-request.Request.prototype.oauth)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>onRequestError (error)](#apidoc.element.co-request.Request.prototype.onRequestError)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>onRequestResponse (response)](#apidoc.element.co-request.Request.prototype.onRequestResponse)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>pause ()](#apidoc.element.co-request.Request.prototype.pause)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>pipe (dest, opts)](#apidoc.element.co-request.Request.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>pipeDest (dest)](#apidoc.element.co-request.Request.prototype.pipeDest)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>qs (q, clobber)](#apidoc.element.co-request.Request.prototype.qs)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>readResponseBody (response)](#apidoc.element.co-request.Request.prototype.readResponseBody)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>resume ()](#apidoc.element.co-request.Request.prototype.resume)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>start ()](#apidoc.element.co-request.Request.prototype.start)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>toJSON ()](#apidoc.element.co-request.Request.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>write ()](#apidoc.element.co-request.Request.prototype.write)



# <a name="apidoc.module.co-request"></a>[module co-request](#apidoc.module.co-request)

#### <a name="apidoc.element.co-request.Request"></a>[function <span class="apidocSignatureSpan">co-request.</span>Request (options)](#apidoc.element.co-request.Request)
- description and source-code
```javascript
function Request(options) {
  // if given the method property in options, set property explicitMethod to true

  // extend the Request instance with any non-reserved properties
  // remove any reserved functions from the options object
  // set Request instance to be readable and writable
  // call init

  var self = this

  // start with HAR, then override with additional options
  if (options.har) {
    self._har = new Har(self)
    options = self._har.options(options)
  }

  stream.Stream.call(self)
  var reserved = Object.keys(Request.prototype)
  var nonReserved = filterForNonReserved(reserved, options)

  extend(self, nonReserved)
  options = filterOutReservedFunctions(reserved, options)

  self.readable = true
  self.writable = true
  if (options.method) {
    self.explicitMethod = true
  }
  self._qs = new Querystring(self)
  self._auth = new Auth(self)
  self._oauth = new OAuth(self)
  self._multipart = new Multipart(self)
  self._redirect = new Redirect(self)
  self._tunnel = new Tunnel(self)
  self.init(options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.cookie"></a>[function <span class="apidocSignatureSpan">co-request.</span>cookie (str)](#apidoc.element.co-request.cookie)
- description and source-code
```javascript
cookie = function (str) {
  return cookies.parse(str)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.defaults"></a>[function <span class="apidocSignatureSpan">co-request.</span>defaults ()](#apidoc.element.co-request.defaults)
- description and source-code
```javascript
defaults = function () {
    return promisifyRequest(request.defaults.apply(request, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.del"></a>[function <span class="apidocSignatureSpan">co-request.</span>del ()](#apidoc.element.co-request.del)
- description and source-code
```javascript
del = function () {
    let args = __slice.call(arguments); //Array.from(arguments) is not available.

    return new Promise(function (resolve, reject) {

        // Concatenate the callback manually to avoid array arguments from co.
        return fn.apply(context, args.concat(function (err) {
            if (err) {
                reject(err);
            } else {
                resolve.apply(this, __slice.call(arguments, 1));
            }
        }));
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.forever"></a>[function <span class="apidocSignatureSpan">co-request.</span>forever ()](#apidoc.element.co-request.forever)
- description and source-code
```javascript
forever = function () {
    return promisifyRequest(request.forever.apply(request, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.get"></a>[function <span class="apidocSignatureSpan">co-request.</span>get ()](#apidoc.element.co-request.get)
- description and source-code
```javascript
get = function () {
    let args = __slice.call(arguments); //Array.from(arguments) is not available.

    return new Promise(function (resolve, reject) {

        // Concatenate the callback manually to avoid array arguments from co.
        return fn.apply(context, args.concat(function (err) {
            if (err) {
                reject(err);
            } else {
                resolve.apply(this, __slice.call(arguments, 1));
            }
        }));
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.head"></a>[function <span class="apidocSignatureSpan">co-request.</span>head ()](#apidoc.element.co-request.head)
- description and source-code
```javascript
head = function () {
    let args = __slice.call(arguments); //Array.from(arguments) is not available.

    return new Promise(function (resolve, reject) {

        // Concatenate the callback manually to avoid array arguments from co.
        return fn.apply(context, args.concat(function (err) {
            if (err) {
                reject(err);
            } else {
                resolve.apply(this, __slice.call(arguments, 1));
            }
        }));
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.jar"></a>[function <span class="apidocSignatureSpan">co-request.</span>jar (store)](#apidoc.element.co-request.jar)
- description and source-code
```javascript
jar = function (store) {
  return cookies.jar(store)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.patch"></a>[function <span class="apidocSignatureSpan">co-request.</span>patch ()](#apidoc.element.co-request.patch)
- description and source-code
```javascript
patch = function () {
    let args = __slice.call(arguments); //Array.from(arguments) is not available.

    return new Promise(function (resolve, reject) {

        // Concatenate the callback manually to avoid array arguments from co.
        return fn.apply(context, args.concat(function (err) {
            if (err) {
                reject(err);
            } else {
                resolve.apply(this, __slice.call(arguments, 1));
            }
        }));
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.post"></a>[function <span class="apidocSignatureSpan">co-request.</span>post ()](#apidoc.element.co-request.post)
- description and source-code
```javascript
post = function () {
    let args = __slice.call(arguments); //Array.from(arguments) is not available.

    return new Promise(function (resolve, reject) {

        // Concatenate the callback manually to avoid array arguments from co.
        return fn.apply(context, args.concat(function (err) {
            if (err) {
                reject(err);
            } else {
                resolve.apply(this, __slice.call(arguments, 1));
            }
        }));
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.put"></a>[function <span class="apidocSignatureSpan">co-request.</span>put ()](#apidoc.element.co-request.put)
- description and source-code
```javascript
put = function () {
    let args = __slice.call(arguments); //Array.from(arguments) is not available.

    return new Promise(function (resolve, reject) {

        // Concatenate the callback manually to avoid array arguments from co.
        return fn.apply(context, args.concat(function (err) {
            if (err) {
                reject(err);
            } else {
                resolve.apply(this, __slice.call(arguments, 1));
            }
        }));
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.co-request.Request"></a>[module co-request.Request](#apidoc.module.co-request.Request)

#### <a name="apidoc.element.co-request.Request.Request"></a>[function <span class="apidocSignatureSpan">co-request.</span>Request (options)](#apidoc.element.co-request.Request.Request)
- description and source-code
```javascript
function Request(options) {
  // if given the method property in options, set property explicitMethod to true

  // extend the Request instance with any non-reserved properties
  // remove any reserved functions from the options object
  // set Request instance to be readable and writable
  // call init

  var self = this

  // start with HAR, then override with additional options
  if (options.har) {
    self._har = new Har(self)
    options = self._har.options(options)
  }

  stream.Stream.call(self)
  var reserved = Object.keys(Request.prototype)
  var nonReserved = filterForNonReserved(reserved, options)

  extend(self, nonReserved)
  options = filterOutReservedFunctions(reserved, options)

  self.readable = true
  self.writable = true
  if (options.method) {
    self.explicitMethod = true
  }
  self._qs = new Querystring(self)
  self._auth = new Auth(self)
  self._oauth = new OAuth(self)
  self._multipart = new Multipart(self)
  self._redirect = new Redirect(self)
  self._tunnel = new Tunnel(self)
  self.init(options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.super_"></a>[function <span class="apidocSignatureSpan">co-request.Request.</span>super_ ()](#apidoc.element.co-request.Request.super_)
- description and source-code
```javascript
function Stream() {
  EE.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.co-request.Request.prototype"></a>[module co-request.Request.prototype](#apidoc.module.co-request.Request.prototype)

#### <a name="apidoc.element.co-request.Request.prototype.abort"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>abort ()](#apidoc.element.co-request.Request.prototype.abort)
- description and source-code
```javascript
abort = function () {
  var self = this
  self._aborted = true

  if (self.req) {
    self.req.abort()
  }
  else if (self.response) {
    self.response.destroy()
  }

  self.emit('abort')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.auth"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>auth (user, pass, sendImmediately, bearer)](#apidoc.element.co-request.Request.prototype.auth)
- description and source-code
```javascript
auth = function (user, pass, sendImmediately, bearer) {
  var self = this

  self._auth.onRequest(user, pass, sendImmediately, bearer)

  return self
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.aws"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>aws (opts, now)](#apidoc.element.co-request.Request.prototype.aws)
- description and source-code
```javascript
aws = function (opts, now) {
  var self = this

  if (!now) {
    self._aws = opts
    return self
  }

  if (opts.sign_version == 4 || opts.sign_version == '4') {
    // use aws4
    var options = {
      host: self.uri.host,
      path: self.uri.path,
      method: self.method,
      headers: {
        'content-type': self.getHeader('content-type') || ''
      },
      body: self.body
    }
    var signRes = aws4.sign(options, {
      accessKeyId: opts.key,
      secretAccessKey: opts.secret,
      sessionToken: opts.session
    })
    self.setHeader('authorization', signRes.headers.Authorization)
    self.setHeader('x-amz-date', signRes.headers['X-Amz-Date'])
    if (signRes.headers['X-Amz-Security-Token']) {
      self.setHeader('x-amz-security-token', signRes.headers['X-Amz-Security-Token'])
    }
  }
  else {
    // default: use aws-sign2
    var date = new Date()
    self.setHeader('date', date.toUTCString())
    var auth =
      { key: opts.key
      , secret: opts.secret
      , verb: self.method.toUpperCase()
      , date: date
      , contentType: self.getHeader('content-type') || ''
      , md5: self.getHeader('content-md5') || ''
      , amazonHeaders: aws2.canonicalizeHeaders(self.headers)
      }
    var path = self.uri.path
    if (opts.bucket && path) {
      auth.resource = '/' + opts.bucket + path
    } else if (opts.bucket && !path) {
      auth.resource = '/' + opts.bucket
    } else if (!opts.bucket && path) {
      auth.resource = path
    } else if (!opts.bucket && !path) {
      auth.resource = '/'
    }
    auth.resource = aws2.canonicalizeResource(auth.resource)
    self.setHeader('authorization', aws2.authorization(auth))
  }

  return self
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.debug"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>debug ()](#apidoc.element.co-request.Request.prototype.debug)
- description and source-code
```javascript
function debug() {
  if (Request.debug) {
    console.error('REQUEST %s', util.format.apply(util, arguments))
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.destroy"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>destroy ()](#apidoc.element.co-request.Request.prototype.destroy)
- description and source-code
```javascript
destroy = function () {
  var self = this
  if (!self._ended) {
    self.end()
  } else if (self.response) {
    self.response.destroy()
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.enableUnixSocket"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>enableUnixSocket ()](#apidoc.element.co-request.Request.prototype.enableUnixSocket)
- description and source-code
```javascript
enableUnixSocket = function () {
  // Get the socket & request paths from the URL
  var unixParts = this.uri.path.split(':')
    , host = unixParts[0]
    , path = unixParts[1]
  // Apply unix properties to request
  this.socketPath = host
  this.uri.pathname = path
  this.uri.path = path
  this.uri.host = host
  this.uri.hostname = host
  this.uri.isUnix = true
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.end"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>end (chunk)](#apidoc.element.co-request.Request.prototype.end)
- description and source-code
```javascript
end = function (chunk) {
  var self = this
  if (self._aborted) {return}

  if (chunk) {
    self.write(chunk)
  }
  if (!self._started) {
    self.start()
  }
  if (self.req) {
    self.req.end()
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.form"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>form (form)](#apidoc.element.co-request.Request.prototype.form)
- description and source-code
```javascript
form = function (form) {
  var self = this
  if (form) {
    if (!/^application\/x-www-form-urlencoded\b/.test(self.getHeader('content-type'))) {
      self.setHeader('content-type', 'application/x-www-form-urlencoded')
    }
    self.body = (typeof form === 'string')
      ? self._qs.rfc3986(form.toString('utf8'))
      : self._qs.stringify(form).toString('utf8')
    return self
  }
  // create form-data object
  self._form = new FormData()
  self._form.on('error', function(err) {
    err.message = 'form-data: ' + err.message
    self.emit('error', err)
    self.abort()
  })
  return self._form
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.getHeader"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>getHeader (name, headers)](#apidoc.element.co-request.Request.prototype.getHeader)
- description and source-code
```javascript
getHeader = function (name, headers) {
  var self = this
  var result, re, match
  if (!headers) {
    headers = self.headers
  }
  Object.keys(headers).forEach(function (key) {
    if (key.length !== name.length) {
      return
    }
    re = new RegExp(name, 'i')
    match = key.match(re)
    if (match) {
      result = headers[key]
    }
  })
  return result
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.getNewAgent"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>getNewAgent ()](#apidoc.element.co-request.Request.prototype.getNewAgent)
- description and source-code
```javascript
getNewAgent = function () {
  var self = this
  var Agent = self.agentClass
  var options = {}
  if (self.agentOptions) {
    for (var i in self.agentOptions) {
      options[i] = self.agentOptions[i]
    }
  }
  if (self.ca) {
    options.ca = self.ca
  }
  if (self.ciphers) {
    options.ciphers = self.ciphers
  }
  if (self.secureProtocol) {
    options.secureProtocol = self.secureProtocol
  }
  if (self.secureOptions) {
    options.secureOptions = self.secureOptions
  }
  if (typeof self.rejectUnauthorized !== 'undefined') {
    options.rejectUnauthorized = self.rejectUnauthorized
  }

  if (self.cert && self.key) {
    options.key = self.key
    options.cert = self.cert
  }

  if (self.pfx) {
    options.pfx = self.pfx
  }

  if (self.passphrase) {
    options.passphrase = self.passphrase
  }

  var poolKey = ''

  // different types of agents are in different pools
  if (Agent !== self.httpModule.Agent) {
    poolKey += Agent.name
  }

  // ca option is only relevant if proxy or destination are https
  var proxy = self.proxy
  if (typeof proxy === 'string') {
    proxy = url.parse(proxy)
  }
  var isHttps = (proxy && proxy.protocol === 'https:') || this.uri.protocol === 'https:'

  if (isHttps) {
    if (options.ca) {
      if (poolKey) {
        poolKey += ':'
      }
      poolKey += options.ca
    }

    if (typeof options.rejectUnauthorized !== 'undefined') {
      if (poolKey) {
        poolKey += ':'
      }
      poolKey += options.rejectUnauthorized
    }

    if (options.cert) {
      if (poolKey) {
        poolKey += ':'
      }
      poolKey += options.cert.toString('ascii') + options.key.toString('ascii')
    }

    if (options.pfx) {
      if (poolKey) {
        poolKey += ':'
      }
      poolKey += options.pfx.toString('ascii')
    }

    if (options.ciphers) {
      if (poolKey) {
        poolKey += ':'
      }
      poolKey += options.ciphers
    }

    if (options.secureProtocol) {
      if (poolKey) {
        poolKey += ':'
      }
      poolKey += options.secureProtocol
    }

    if (options.secureOptions) {
      if (poolKey) {
        poolKey += ':'
      }
      poolKey += options.secureOptions
    }
  }

  if (self.pool === globalPool && !poolKey && Object.keys(options).length === 0 && self.httpModule.globalAgent) {
    // not doing anything special.  Use the globalAgent
    return self.httpModule.globalAgent
  }

  // we're using a stored agent.  Make sure it's protocol-specific
  poolKey = self.uri.protocol + poolKey

  // generate a new agent for this setting if none yet exists
  if (!self.pool[poolKey]) {
    self.pool[poolKey] = new Agent(options)
    // properly set maxSockets on new agents
    if (self.pool.maxSockets) {
      self.pool[poolKey].maxSockets = self.pool.maxSockets
    }
  }

  return self.pool[poolKey]
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.hawk"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>hawk (opts)](#apidoc.element.co-request.Request.prototype.hawk)
- description and source-code
```javascript
hawk = function (opts) {
  var self = this
  self.setHeader('Authorization', hawk.client.header(self.uri, self.method, opts).field)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.httpSignature"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>httpSignature (opts)](#apidoc.element.co-request.Request.prototype.httpSignature)
- description and source-code
```javascript
httpSignature = function (opts) {
  var self = this
  httpSignature.signRequest({
    getHeader: function(header) {
      return self.getHeader(header, self.headers)
    },
    setHeader: function(header, value) {
      self.setHeader(header, value)
    },
    method: self.method,
    path: self.path
  }, opts)
  debug('httpSignature authorization', self.getHeader('authorization'))

  return self
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.init"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>init (options)](#apidoc.element.co-request.Request.prototype.init)
- description and source-code
```javascript
init = function (options) {
  // init() contains all the code to setup the request object.
  // the actual outgoing request is not started until start() is called
  // this function is called from both the constructor and on redirect.
  var self = this
  if (!options) {
    options = {}
  }
  self.headers = self.headers ? copy(self.headers) : {}

  // Delete headers with value undefined since they break
  // ClientRequest.OutgoingMessage.setHeader in node 0.12
  for (var headerName in self.headers) {
    if (typeof self.headers[headerName] === 'undefined') {
      delete self.headers[headerName]
    }
  }

  caseless.httpify(self, self.headers)

  if (!self.method) {
    self.method = options.method || 'GET'
  }
  if (!self.localAddress) {
    self.localAddress = options.localAddress
  }

  self._qs.init(options)

  debug(options)
  if (!self.pool && self.pool !== false) {
    self.pool = globalPool
  }
  self.dests = self.dests || []
  self.__isRequestRequest = true

  // Protect against double callback
  if (!self._callback && self.callback) {
    self._callback = self.callback
    self.callback = function () {
      if (self._callbackCalled) {
        return // Print a warning maybe?
      }
      self._callbackCalled = true
      self._callback.apply(self, arguments)
    }
    self.on('error', self.callback.bind())
    self.on('complete', self.callback.bind(self, null))
  }

  // People use this property instead all the time, so support it
  if (!self.uri && self.url) {
    self.uri = self.url
    delete self.url
  }

  // If there's a baseUrl, then use it as the base URL (i.e. uri must be
  // specified as a relative path and is appended to baseUrl).
  if (self.baseUrl) {
    if (typeof self.baseUrl !== 'string') {
      return self.emit('error', new Error('options.baseUrl must be a string'))
    }

    if (typeof self.uri !== 'string') {
      return self.emit('error', new Error('options.uri must be a string when using options.baseUrl'))
    }

    if (self.uri.indexOf('//') === 0 || self.uri.indexOf('://') !== -1) {
      return self.emit('error', new Error('options.uri must be a path when using options.baseUrl'))
    }

    // Handle all cases to make sure that there's only one slash between
    // baseUrl and uri.
    var baseUrlEndsWithSlash = self.baseUrl.lastIndexOf('/') === self.baseUrl.length - 1
    var uriStartsWithSlash = self.uri.indexOf('/') === 0

    if (baseUrlEndsWithSlash && uriStartsWithSlash) {
      self.uri = self.baseUrl + self.uri.slice(1)
    } else if (baseUrlEndsWithSlash || uriStartsWithSlash) {
      self.uri = self.baseUrl + self.uri
    } else if (self.uri === '') {
      self.uri = self.baseUrl
    } else {
      self.uri = self.baseUrl + '/' + self.uri
    }
    delete self.baseUrl
  }

  // A URI is needed by this point, emit error if we haven't been able to get one
  if (!self.uri) {
    return self.emit('error', new Error('options.uri is a required argument'))
  }

  // If a string URI/URL was given, parse it into a URL object
  if (typeof self.uri === 'string') {
    self.uri = url.parse(self.uri)
  }

  // Some URL objects are not from a URL parsed string and need href added
  if (!self.uri.href) {
    self.uri.href = url.format(self.uri)
  }

  // DEPRECATED: Warning for users of the old Unix Sockets URL Scheme
  if (self.uri.protocol === 'unix:') {
    return self.emit('error', new Error(''unix://' URL scheme is no longer supported. Please use the format 'http://unix:SOCKET:
PATH''))
  }

  // Support Unix Sockets
  if (self.uri.host === 'unix') {
    self.enableUnixSocket()
  }

  if (self.strictSSL === false) {
    self.rejectUnauthorized = false
  }

  if (!self.uri.pathname) {self.uri.pathname = '/'}

  if (!(self.uri.host || (self.uri.hostname && self.uri.port)) && !self.uri.isUnix) {
    // Invalid URI: it may generate lot of bad errors, like 'TypeError: Cannot call method 'indexOf' of undefined' in CookieJar
    // Detect and reject it as soon as possible
    var faultyUri = url.format(self.uri)
    var message = 'Invalid URI "' + faultyUri + '"'
    if (Object.keys(options). ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.jar"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>jar (jar)](#apidoc.element.co-request.Request.prototype.jar)
- description and source-code
```javascript
jar = function (jar) {
  var self = this
  var cookies

  if (self._redirect.redirectsFollowed === 0) {
    self.originalCookieHeader = self.getHeader('cookie')
  }

  if (!jar) {
    // disable cookies
    cookies = false
    self._disableCookies = true
  } else {
    var targetCookieJar = (jar && jar.getCookieString) ? jar : globalCookieJar
    var urihref = self.uri.href
    //fetch cookie in the Specified host
    if (targetCookieJar) {
      cookies = targetCookieJar.getCookieString(urihref)
    }
  }

  //if need cookie and cookie is not empty
  if (cookies && cookies.length) {
    if (self.originalCookieHeader) {
      // Don't overwrite existing Cookie header
      self.setHeader('cookie', self.originalCookieHeader + '; ' + cookies)
    } else {
      self.setHeader('cookie', cookies)
    }
  }
  self._jar = jar
  return self
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.json"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>json (val)](#apidoc.element.co-request.Request.prototype.json)
- description and source-code
```javascript
json = function (val) {
  var self = this

  if (!self.hasHeader('accept')) {
    self.setHeader('accept', 'application/json')
  }

  if (typeof self.jsonReplacer === 'function') {
    self._jsonReplacer = self.jsonReplacer
  }

  self._json = true
  if (typeof val === 'boolean') {
    if (self.body !== undefined) {
      if (!/^application\/x-www-form-urlencoded\b/.test(self.getHeader('content-type'))) {
        self.body = safeStringify(self.body, self._jsonReplacer)
      } else {
        self.body = self._qs.rfc3986(self.body)
      }
      if (!self.hasHeader('content-type')) {
        self.setHeader('content-type', 'application/json')
      }
    }
  } else {
    self.body = safeStringify(val, self._jsonReplacer)
    if (!self.hasHeader('content-type')) {
      self.setHeader('content-type', 'application/json')
    }
  }

  if (typeof self.jsonReviver === 'function') {
    self._jsonReviver = self.jsonReviver
  }

  return self
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.multipart"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>multipart (multipart)](#apidoc.element.co-request.Request.prototype.multipart)
- description and source-code
```javascript
multipart = function (multipart) {
  var self = this

  self._multipart.onRequest(multipart)

  if (!self._multipart.chunked) {
    self.body = self._multipart.body
  }

  return self
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.oauth"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>oauth (_oauth)](#apidoc.element.co-request.Request.prototype.oauth)
- description and source-code
```javascript
oauth = function (_oauth) {
  var self = this

  self._oauth.onRequest(_oauth)

  return self
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.onRequestError"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>onRequestError (error)](#apidoc.element.co-request.Request.prototype.onRequestError)
- description and source-code
```javascript
onRequestError = function (error) {
  var self = this
  if (self._aborted) {
    return
  }
  if (self.req && self.req._reusedSocket && error.code === 'ECONNRESET'
      && self.agent.addRequestNoreuse) {
    self.agent = { addRequest: self.agent.addRequestNoreuse.bind(self.agent) }
    self.start()
    self.req.end()
    return
  }
  if (self.timeout && self.timeoutTimer) {
    clearTimeout(self.timeoutTimer)
    self.timeoutTimer = null
  }
  self.emit('error', error)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.onRequestResponse"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>onRequestResponse (response)](#apidoc.element.co-request.Request.prototype.onRequestResponse)
- description and source-code
```javascript
onRequestResponse = function (response) {
  var self = this

  if (self.timing) {
    self.timings.response = now() - self.startTimeNow
  }

  debug('onRequestResponse', self.uri.href, response.statusCode, response.headers)
  response.on('end', function() {
    if (self.timing) {
      self.timings.end = now() - self.startTimeNow
      response.timingStart = self.startTime

      // fill in the blanks for any periods that didn't trigger, such as
      // no lookup or connect due to keep alive
      if (!self.timings.socket) {
        self.timings.socket = 0
      }
      if (!self.timings.lookup) {
        self.timings.lookup = self.timings.socket
      }
      if (!self.timings.connect) {
        self.timings.connect = self.timings.lookup
      }
      if (!self.timings.response) {
        self.timings.response = self.timings.connect
      }

      debug('elapsed time', self.timings.end)

      // elapsedTime includes all redirects
      self.elapsedTime += Math.round(self.timings.end)

      // NOTE: elapsedTime is deprecated in favor of .timings
      response.elapsedTime = self.elapsedTime

      // timings is just for the final fetch
      response.timings = self.timings

      // pre-calculate phase timings as well
      response.timingPhases = {
        wait: self.timings.socket,
        dns: self.timings.lookup - self.timings.socket,
        tcp: self.timings.connect - self.timings.lookup,
        firstByte: self.timings.response - self.timings.connect,
        download: self.timings.end - self.timings.response,
        total: self.timings.end
      }
    }
    debug('response end', self.uri.href, response.statusCode, response.headers)
  })

  if (self._aborted) {
    debug('aborted', self.uri.href)
    response.resume()
    return
  }

  self.response = response
  response.request = self
  response.toJSON = responseToJSON

  // XXX This is different on 0.10, because SSL is strict by default
  if (self.httpModule === https &&
      self.strictSSL && (!response.hasOwnProperty('socket') ||
      !response.socket.authorized)) {
    debug('strict ssl error', self.uri.href)
    var sslErr = response.hasOwnProperty('socket') ? response.socket.authorizationError : self.uri.href + ' does not support SSL
'
    self.emit('error', new Error('SSL Error: ' + sslErr))
    return
  }

  // Save the original host before any redirect (if it changes, we need to
  // remove any authorization headers).  Also remember the case of the header
  // name because lots of broken servers expect Host instead of host and we
  // want the caller to be able to specify this.
  self.originalHost = self.getHeader('host')
  if (!self.originalHostHeaderName) {
    self.originalHostHeaderName = self.hasHeader('host')
  }
  if (self.setHost) {
    self.removeHeader('host')
  }
  if (self.timeout && self.timeoutTimer) {
    clearTimeout(self.timeoutTimer)
    self.timeoutTimer = null
  }

  var targetCookieJar = (self._jar && self._jar.setCookie) ? self._jar : globalCookieJar
  var addCookie = function (cookie) {
    //set the cookie if it's domain in the href's domain.
    try {
      targetCookieJar.setCookie(cookie, self.uri.href, {ignoreError: true})
    } catch (e) {
      self.emit('error', e)
    }
  }

  response.caseless = caseless(response.headers)

  if (response.caseless.has('set-cookie') && (!self._disableCookies)) {
    var headerName = response.caseless.has('set-cookie')
    if (Array.isArray(response.headers[headerName])) {
      response.headers[headerName].forEach(addCookie)
    } else {
      addCookie(response.headers[headerName])
    }
  }

  if (self._redirect.onResponse(response)) {
    return // Ignore the rest of the response
  } else {
    // Be a good stream and emit end when the response is finished.
    // Hack to emit end on close because of a core bug that never fires end
    response.on('close', function () {
      if (!self._ended) {
        self.response.emit('end')
      }
    })

    response.once('end', function () {
      self._ended = true
    })

    var noBody = function (code) {
      return (
        self.method === 'HEAD' ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.pause"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>pause ()](#apidoc.element.co-request.Request.prototype.pause)
- description and source-code
```javascript
pause = function () {
  var self = this
  if (!self.responseContent) {
    self._paused = true
  } else {
    self.responseContent.pause.apply(self.responseContent, arguments)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.pipe"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>pipe (dest, opts)](#apidoc.element.co-request.Request.prototype.pipe)
- description and source-code
```javascript
pipe = function (dest, opts) {
  var self = this

  if (self.response) {
    if (self._destdata) {
      self.emit('error', new Error('You cannot pipe after data has been emitted from the response.'))
    } else if (self._ended) {
      self.emit('error', new Error('You cannot pipe after the response has been ended.'))
    } else {
      stream.Stream.prototype.pipe.call(self, dest, opts)
      self.pipeDest(dest)
      return dest
    }
  } else {
    self.dests.push(dest)
    stream.Stream.prototype.pipe.call(self, dest, opts)
    return dest
  }
}
```
- example usage
```shell
...
'''

To pipe request you should use small helper (thanks to [greim](https://github.com/greim)):

'''js
function pipeRequest(readable, requestThunk){
  return function(cb){
    readable.pipe(requestThunk(cb));
  }
}

//..and then:

  var value = yield pipeRequest(this.req, request({...}));
'''
...
```

#### <a name="apidoc.element.co-request.Request.prototype.pipeDest"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>pipeDest (dest)](#apidoc.element.co-request.Request.prototype.pipeDest)
- description and source-code
```javascript
pipeDest = function (dest) {
  var self = this
  var response = self.response
  // Called after the response is received
  if (dest.headers && !dest.headersSent) {
    if (response.caseless.has('content-type')) {
      var ctname = response.caseless.has('content-type')
      if (dest.setHeader) {
        dest.setHeader(ctname, response.headers[ctname])
      }
      else {
        dest.headers[ctname] = response.headers[ctname]
      }
    }

    if (response.caseless.has('content-length')) {
      var clname = response.caseless.has('content-length')
      if (dest.setHeader) {
        dest.setHeader(clname, response.headers[clname])
      } else {
        dest.headers[clname] = response.headers[clname]
      }
    }
  }
  if (dest.setHeader && !dest.headersSent) {
    for (var i in response.headers) {
      // If the response content is being decoded, the Content-Encoding header
      // of the response doesn't represent the piped content, so don't pass it.
      if (!self.gzip || i !== 'content-encoding') {
        dest.setHeader(i, response.headers[i])
      }
    }
    dest.statusCode = response.statusCode
  }
  if (self.pipefilter) {
    self.pipefilter(response, dest)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.qs"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>qs (q, clobber)](#apidoc.element.co-request.Request.prototype.qs)
- description and source-code
```javascript
qs = function (q, clobber) {
  var self = this
  var base
  if (!clobber && self.uri.query) {
    base = self._qs.parse(self.uri.query)
  } else {
    base = {}
  }

  for (var i in q) {
    base[i] = q[i]
  }

  var qs = self._qs.stringify(base)

  if (qs === '') {
    return self
  }

  self.uri = url.parse(self.uri.href.split('?')[0] + '?' + qs)
  self.url = self.uri
  self.path = self.uri.path

  if (self.uri.host === 'unix') {
    self.enableUnixSocket()
  }

  return self
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.readResponseBody"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>readResponseBody (response)](#apidoc.element.co-request.Request.prototype.readResponseBody)
- description and source-code
```javascript
readResponseBody = function (response) {
  var self = this
  debug('reading response\'s body')
  var buffers = []
    , bufferLength = 0
    , strings = []

  self.on('data', function (chunk) {
    if (!Buffer.isBuffer(chunk)) {
      strings.push(chunk)
    } else if (chunk.length) {
      bufferLength += chunk.length
      buffers.push(chunk)
    }
  })
  self.on('end', function () {
    debug('end event', self.uri.href)
    if (self._aborted) {
      debug('aborted', self.uri.href)
      // 'buffer' is defined in the parent scope and used in a closure it exists for the life of the request.
      // This can lead to leaky behavior if the user retains a reference to the request object.
      buffers = []
      bufferLength = 0
      return
    }

    if (bufferLength) {
      debug('has body', self.uri.href, bufferLength)
      response.body = Buffer.concat(buffers, bufferLength)
      if (self.encoding !== null) {
        response.body = response.body.toString(self.encoding)
      }
      // 'buffer' is defined in the parent scope and used in a closure it exists for the life of the Request.
      // This can lead to leaky behavior if the user retains a reference to the request object.
      buffers = []
      bufferLength = 0
    } else if (strings.length) {
      // The UTF8 BOM [0xEF,0xBB,0xBF] is converted to [0xFE,0xFF] in the JS UTC16/UCS2 representation.
      // Strip this value out when the encoding is set to 'utf8', as upstream consumers won't expect it and it breaks JSON.parse
().
      if (self.encoding === 'utf8' && strings[0].length > 0 && strings[0][0] === '\uFEFF') {
        strings[0] = strings[0].substring(1)
      }
      response.body = strings.join('')
    }

    if (self._json) {
      try {
        response.body = JSON.parse(response.body, self._jsonReviver)
      } catch (e) {
        debug('invalid JSON received', self.uri.href)
      }
    }
    debug('emitting complete', self.uri.href)
    if (typeof response.body === 'undefined' && !self._json) {
      response.body = self.encoding === null ? Buffer.alloc(0) : ''
    }
    self.emit('complete', response, response.body)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.resume"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>resume ()](#apidoc.element.co-request.Request.prototype.resume)
- description and source-code
```javascript
resume = function () {
  var self = this
  if (!self.responseContent) {
    self._paused = false
  } else {
    self.responseContent.resume.apply(self.responseContent, arguments)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.start"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>start ()](#apidoc.element.co-request.Request.prototype.start)
- description and source-code
```javascript
start = function () {
  // start() is called once we are ready to send the outgoing HTTP request.
  // this is usually called on the first write(), end() or on nextTick()
  var self = this

  if (self.timing) {
    // All timings will be relative to this request's startTime.  In order to do this,
    // we need to capture the wall-clock start time (via Date), immediately followed
    // by the high-resolution timer (via now()).  While these two won't be set
    // at the _exact_ same time, they should be close enough to be able to calculate
    // high-resolution, monotonically non-decreasing timestamps relative to startTime.
    var startTime = new Date().getTime()
    var startTimeNow = now()
  }

  if (self._aborted) {
    return
  }

  self._started = true
  self.method = self.method || 'GET'
  self.href = self.uri.href

  if (self.src && self.src.stat && self.src.stat.size && !self.hasHeader('content-length')) {
    self.setHeader('content-length', self.src.stat.size)
  }
  if (self._aws) {
    self.aws(self._aws, true)
  }

  // We have a method named auth, which is completely different from the http.request
  // auth option.  If we don't remove it, we're gonna have a bad time.
  var reqOptions = copy(self)
  delete reqOptions.auth

  debug('make request', self.uri.href)

  // node v6.8.0 now supports a 'timeout' value in 'http.request()', but we
  // should delete it for now since we handle timeouts manually for better
  // consistency with node versions before v6.8.0
  delete reqOptions.timeout

  try {
    self.req = self.httpModule.request(reqOptions)
  } catch (err) {
    self.emit('error', err)
    return
  }

  if (self.timing) {
    self.startTime = startTime
    self.startTimeNow = startTimeNow

    // Timing values will all be relative to startTime (by comparing to startTimeNow
    // so we have an accurate clock)
    self.timings = {}
  }

  var timeout
  if (self.timeout && !self.timeoutTimer) {
    if (self.timeout < 0) {
      timeout = 0
    } else if (typeof self.timeout === 'number' && isFinite(self.timeout)) {
      timeout = self.timeout
    }
  }

  self.req.on('response', self.onRequestResponse.bind(self))
  self.req.on('error', self.onRequestError.bind(self))
  self.req.on('drain', function() {
    self.emit('drain')
  })
  self.req.on('socket', function(socket) {
    // '._connecting' was the old property which was made public in node v6.1.0
    var isConnecting = socket._connecting || socket.connecting
    if (self.timing) {
      self.timings.socket = now() - self.startTimeNow

      if (isConnecting) {
        var onLookupTiming = function() {
          self.timings.lookup = now() - self.startTimeNow
        }

        var onConnectTiming = function() {
          self.timings.connect = now() - self.startTimeNow
        }

        socket.once('lookup', onLookupTiming)
        socket.once('connect', onConnectTiming)

        // clean up timing event listeners if needed on error
        self.req.once('error', function() {
          socket.removeListener('lookup', onLookupTiming)
          socket.removeListener('connect', onConnectTiming)
        })
      }
    }

    var setReqTimeout = function() {
      // This timeout sets the amount of time to wait *between* bytes sent
      // from the server once connected.
      //
      // In particular, it's useful for erroring if the server fails to send
      // data halfway through streaming a response.
      self.req.setTimeout(timeout, function () {
        if (self.req) {
          self.abort()
          var e = new Error('ESOCKETTIMEDOUT')
          e.code = 'ESOCKETTIMEDOUT'
          e.connect = false
          self.emit('error', e)
        }
      })
    }
    if (timeout !== undefined) {
      // Only start the connection timer if we're actually connecting a new
      // socket, otherwise if we're already connected (because this is a
      // keep-alive connection) do not bother. This is important since we won't
      // get a 'connect' event for an already connected socket.
      if (isConnecting) {
        var onReqSockConnect = function() { ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>toJSON ()](#apidoc.element.co-request.Request.prototype.toJSON)
- description and source-code
```javascript
function requestToJSON() {
  var self = this
  return {
    uri: self.uri,
    method: self.method,
    headers: self.headers
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.co-request.Request.prototype.write"></a>[function <span class="apidocSignatureSpan">co-request.Request.prototype.</span>write ()](#apidoc.element.co-request.Request.prototype.write)
- description and source-code
```javascript
write = function () {
  var self = this
  if (self._aborted) {return}

  if (!self._started) {
    self.start()
  }
  if (self.req) {
    return self.req.write.apply(self.req, arguments)
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# api documentation for  [bcrypt (v1.0.2)](https://github.com/kelektiv/node.bcrypt.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-bcrypt.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bcrypt) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bcrypt.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bcrypt)
#### A bcrypt library for NodeJS.

[![NPM](https://nodei.co/npm/bcrypt.png?downloads=true)](https://www.npmjs.com/package/bcrypt)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bcrypt/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-bcrypt_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bcrypt/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bcrypt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bcrypt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Campbell",
        "url": "https://github.com/ncb000gt"
    },
    "binary": {
        "module_name": "bcrypt_lib",
        "module_path": "./lib/binding/",
        "host": "https://github.com",
        "remote_path": "/kelektiv/node.bcrypt.js/releases/download/v{version}/"
    },
    "bugs": {
        "url": "https://github.com/kelektiv/node.bcrypt.js/issues"
    },
    "contributors": [
        {
            "name": "Antonio Salazar Cardozo",
            "email": "savedfastcool@gmail.com",
            "url": "https://github.com/Shadowfiend"
        },
        {
            "name": "Van Nguyen",
            "email": "the.gol.effect@gmail.com",
            "url": "https://github.com/thegoleffect"
        },
        {
            "name": "David Trejo",
            "email": "david@dtrejo.com",
            "url": "https://github.com/dtrejo"
        },
        {
            "name": "Ben Glow",
            "email": "glen.low@pixelglow.com",
            "url": "https://github.com/pixelglow"
        },
        {
            "name": "NewITFarmer.com",
            "url": "https://github.com/newitfarmer"
        },
        {
            "name": "Alfred Westerveld",
            "email": "alfredwesterveld@gmail.com",
            "url": "https://github.com/alfredwesterveld"
        },
        {
            "name": "Vincent Côté-Roy",
            "email": "vincentcr@gmail.com",
            "url": "https://github.com/vincentcr"
        },
        {
            "name": "Lloyd Hilaiel",
            "email": "lloyd@hilaiel.com",
            "url": "https://github.com/lloyd"
        },
        {
            "name": "Roman Shtylman",
            "email": "shtylman@gmail.com",
            "url": "https://github.com/shtylman"
        },
        {
            "name": "Vadim Graboys",
            "email": "dimva13@gmail.com",
            "url": "https://github.com/vadimg"
        },
        {
            "name": "Ben Noorduis",
            "url": "https://github.com/bnoordhuis"
        },
        {
            "name": "Nate Rajlich",
            "email": "nathan@tootallnate.net",
            "url": "https://github.com/tootallnate"
        },
        {
            "name": "Sean McArthur",
            "email": "sean.monstar@gmail.com",
            "url": "https://github.com/seanmonstar"
        },
        {
            "name": "Fanie Oosthuysen",
            "email": "fanie.oosthuysen@gmail.com",
            "url": "https://github.com/weareu"
        },
        {
            "name": "Amitosh Swain Mahapatra",
            "email": "amitosh.swain@gmail.com",
            "url": "https://github.com/Agathver"
        }
    ],
    "dependencies": {
        "bindings": "1.2.1",
        "nan": "2.5.0",
        "node-pre-gyp": "0.6.32"
    },
    "description": "A bcrypt library for NodeJS.",
    "devDependencies": {
        "nodeunit": "~0.9.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d05fc5d223173e0e28ec381c0f00cc25ffaf2736",
        "tarball": "https://registry.npmjs.org/bcrypt/-/bcrypt-1.0.2.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "gitHead": "9036615a24c51f0d125ae39efbf9b943f16c8571",
    "homepage": "https://github.com/kelektiv/node.bcrypt.js#readme",
    "keywords": [
        "bcrypt",
        "password",
        "auth",
        "authentication",
        "encryption",
        "crypt",
        "crypto"
    ],
    "license": "MIT",
    "main": "./bcrypt",
    "maintainers": [
        {
            "name": "ncb000gt",
            "email": "nicholas.j.campbell@gmail.com"
        },
        {
            "name": "tootallnate",
            "email": "nathan@tootallnate.net"
        },
        {
            "name": "jfirebaugh",
            "email": "john.firebaugh@gmail.com"
        },
        {
            "name": "defunctzombie",
            "email": "shtylman@gmail.com"
        }
    ],
    "name": "bcrypt",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kelektiv/node.bcrypt.js.git"
    },
    "scripts": {
        "install": "node-pre-gyp install --fallback-to-build",
        "test": "npm install --build-from-source && nodeunit test"
    },
    "version": "1.0.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module bcrypt](#apidoc.module.bcrypt)
1.  [function <span class="apidocSignatureSpan">bcrypt.</span>compare (data, hash, cb)](#apidoc.element.bcrypt.compare)
1.  [function <span class="apidocSignatureSpan">bcrypt.</span>compareSync (data, hash)](#apidoc.element.bcrypt.compareSync)
1.  [function <span class="apidocSignatureSpan">bcrypt.</span>genSalt (rounds, ignore, cb)](#apidoc.element.bcrypt.genSalt)
1.  [function <span class="apidocSignatureSpan">bcrypt.</span>genSaltSync (rounds)](#apidoc.element.bcrypt.genSaltSync)
1.  [function <span class="apidocSignatureSpan">bcrypt.</span>getRounds (hash)](#apidoc.element.bcrypt.getRounds)
1.  [function <span class="apidocSignatureSpan">bcrypt.</span>hash (data, salt, cb)](#apidoc.element.bcrypt.hash)
1.  [function <span class="apidocSignatureSpan">bcrypt.</span>hashSync (data, salt)](#apidoc.element.bcrypt.hashSync)
1.  object <span class="apidocSignatureSpan">bcrypt.</span>promises

#### [module bcrypt.promises](#apidoc.module.bcrypt.promises)
1.  [function <span class="apidocSignatureSpan">bcrypt.promises.</span>promise (fn, context, args)](#apidoc.element.bcrypt.promises.promise)
1.  [function <span class="apidocSignatureSpan">bcrypt.promises.</span>reject (err)](#apidoc.element.bcrypt.promises.reject)



# <a name="apidoc.module.bcrypt"></a>[module bcrypt](#apidoc.module.bcrypt)

#### <a name="apidoc.element.bcrypt.compare"></a>[function <span class="apidocSignatureSpan">bcrypt.</span>compare (data, hash, cb)](#apidoc.element.bcrypt.compare)
- description and source-code
```javascript
function compare(data, hash, cb) {
    if (typeof data === 'function') {
        return process.nextTick(function() {
            data(new Error('data and hash arguments required'));
        });
    }

    if (typeof hash === 'function') {
        return process.nextTick(function() {
            hash(new Error('data and hash arguments required'));
        });
    }

    // cb exists but is not a function
    // return a rejecting promise
    if (cb && typeof cb !== 'function') {
        return promises.reject(new Error('cb must be a function or null to return a Promise'));
    }

    if (!cb) {
        return promises.promise(compare, this, [data, hash]);
    }

    if (data == null || hash == null) {
        return process.nextTick(function() {
            cb(new Error('data and hash arguments required'));
        });
    }

    if (typeof data !== 'string' || typeof hash !== 'string') {
        return process.nextTick(function() {
            cb(new Error('data and hash must be strings'));
        });
    }

    return bindings.compare(data, hash, cb);
}
```
- example usage
```shell
...

Note that both techniques achieve the same end-result.

#### To check a password:

'''javascript
// Load hash from your password DB.
bcrypt.compare(myPlaintextPassword, hash, function(err, res) {
    // res == true
});
bcrypt.compare(someOtherPlaintextPassword, hash, function(err, res) {
    // res == false
});
'''
### with promises
...
```

#### <a name="apidoc.element.bcrypt.compareSync"></a>[function <span class="apidocSignatureSpan">bcrypt.</span>compareSync (data, hash)](#apidoc.element.bcrypt.compareSync)
- description and source-code
```javascript
function compareSync(data, hash) {
    if (data == null || hash == null) {
        throw new Error('data and hash arguments required');
    }

    if (typeof data !== 'string' || typeof hash !== 'string') {
        throw new Error('data and hash must be strings');
    }

    return bindings.compare_sync(data, hash);
}
```
- example usage
```shell
...

As with async, both techniques achieve the same end-result.

#### To check a password:

'''javascript
// Load hash from your password DB.
bcrypt.compareSync(myPlaintextPassword, hash); // true
bcrypt.compareSync(someOtherPlaintextPassword, hash); // false
'''

### Why is async mode recommended over sync mode?
If you are using bcrypt on a simple script, using the sync mode is perfectly fine. However, if you are using bcrypt on a server,
the async mode is recommended. This is because the hashing done by bcrypt is CPU intensive, so the sync version will block the event
 loop and prevent your application from servicing any other inbound requests or events.

## API
...
```

#### <a name="apidoc.element.bcrypt.genSalt"></a>[function <span class="apidocSignatureSpan">bcrypt.</span>genSalt (rounds, ignore, cb)](#apidoc.element.bcrypt.genSalt)
- description and source-code
```javascript
function genSalt(rounds, ignore, cb) {
    // if callback is first argument, then use defaults for others
    if (typeof arguments[0] === 'function') {
        // have to set callback first otherwise arguments are overriden
        cb = arguments[0];
        rounds = 10;
    // callback is second argument
    } else if (typeof arguments[1] === 'function') {
        // have to set callback first otherwise arguments are overriden
        cb = arguments[1];
    }

    if (!cb) {
        return promises.promise(genSalt, this, [rounds, ignore]);
    }

    // default 10 rounds
    if (!rounds) {
        rounds = 10;
    } else if (typeof rounds !== 'number') {
        // callback error asynchronously
        return process.nextTick(function() {
            cb(new Error('rounds must be a number'));
        });
    }

    crypto.randomBytes(16, function(error, randomBytes) {
        if (error) {
            cb(error);
            return;
        }

        bindings.gen_salt(rounds, randomBytes, cb);
    });
}
```
- example usage
```shell
...
'''

#### To hash a password:

Technique 1 (generate a salt and hash on separate function calls):

'''javascript
bcrypt.genSalt(saltRounds, function(err, salt) {
    bcrypt.hash(myPlaintextPassword, salt, function(err, hash) {
        // Store hash in your password DB.
    });
});
'''

Technique 2 (auto-gen a salt and hash):
...
```

#### <a name="apidoc.element.bcrypt.genSaltSync"></a>[function <span class="apidocSignatureSpan">bcrypt.</span>genSaltSync (rounds)](#apidoc.element.bcrypt.genSaltSync)
- description and source-code
```javascript
function genSaltSync(rounds) {
    // default 10 rounds
    if (!rounds) {
        rounds = 10;
    } else if (typeof rounds !== 'number') {
        throw new Error('rounds must be a number');
    }

    return bindings.gen_salt_sync(rounds, crypto.randomBytes(16));
}
```
- example usage
```shell
...
'''

#### To hash a password:

Technique 1 (generate a salt and hash on separate function calls):

'''javascript
var salt = bcrypt.genSaltSync(saltRounds);
var hash = bcrypt.hashSync(myPlaintextPassword, salt);
// Store hash in your password DB.
'''

Technique 2 (auto-gen a salt and hash):

'''javascript
...
```

#### <a name="apidoc.element.bcrypt.getRounds"></a>[function <span class="apidocSignatureSpan">bcrypt.</span>getRounds (hash)](#apidoc.element.bcrypt.getRounds)
- description and source-code
```javascript
function getRounds(hash) {
    if (hash == null) {
        throw new Error('hash argument required');
    }

    if (typeof hash !== 'string') {
        throw new Error('hash must be a string');
    }

    return bindings.get_rounds(hash);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bcrypt.hash"></a>[function <span class="apidocSignatureSpan">bcrypt.</span>hash (data, salt, cb)](#apidoc.element.bcrypt.hash)
- description and source-code
```javascript
function hash(data, salt, cb) {
    if (typeof data === 'function') {
        return process.nextTick(function() {
            data(new Error('data must be a string and salt must either be a salt string or a number of rounds'));
        });
    }

    if (typeof salt === 'function') {
        return process.nextTick(function() {
            salt(new Error('data must be a string and salt must either be a salt string or a number of rounds'));
        });
    }

    // cb exists but is not a function
    // return a rejecting promise
    if (cb && typeof cb !== 'function') {
        return promises.reject(new Error('cb must be a function or null to return a Promise'));
    }

    if (!cb) {
        return promises.promise(hash, this, [data, salt]);
    }

    if (data == null || salt == null) {
        return process.nextTick(function() {
            cb(new Error('data and salt arguments required'));
        });
    }

    if (typeof data !== 'string' || (typeof salt !== 'string' && typeof salt !== 'number')) {
        return process.nextTick(function() {
            cb(new Error('data must be a string and salt must either be a salt string or a number of rounds'));
        });
    }


    if (typeof salt === 'number') {
        return module.exports.genSalt(salt, function(err, salt) {
            return bindings.encrypt(data, salt, cb);
        });
    }

    return bindings.encrypt(data, salt, cb);
}
```
- example usage
```shell
...

#### To hash a password:

Technique 1 (generate a salt and hash on separate function calls):

'''javascript
bcrypt.genSalt(saltRounds, function(err, salt) {
    bcrypt.hash(myPlaintextPassword, salt, function(err, hash) {
        // Store hash in your password DB.
    });
});
'''

Technique 2 (auto-gen a salt and hash):
...
```

#### <a name="apidoc.element.bcrypt.hashSync"></a>[function <span class="apidocSignatureSpan">bcrypt.</span>hashSync (data, salt)](#apidoc.element.bcrypt.hashSync)
- description and source-code
```javascript
function hashSync(data, salt) {
    if (data == null || salt == null) {
        throw new Error('data and salt arguments required');
    }

    if (typeof data !== 'string' || (typeof salt !== 'string' && typeof salt !== 'number')) {
        throw new Error('data must be a string and salt must either be a salt string or a number of rounds');
    }

    if (typeof salt === 'number') {
        salt = module.exports.genSaltSync(salt);
    }

    return bindings.encrypt_sync(data, salt);
}
```
- example usage
```shell
...

#### To hash a password:

Technique 1 (generate a salt and hash on separate function calls):

'''javascript
var salt = bcrypt.genSaltSync(saltRounds);
var hash = bcrypt.hashSync(myPlaintextPassword, salt);
// Store hash in your password DB.
'''

Technique 2 (auto-gen a salt and hash):

'''javascript
var hash = bcrypt.hashSync(myPlaintextPassword, saltRounds);
...
```



# <a name="apidoc.module.bcrypt.promises"></a>[module bcrypt.promises](#apidoc.module.bcrypt.promises)

#### <a name="apidoc.element.bcrypt.promises.promise"></a>[function <span class="apidocSignatureSpan">bcrypt.promises.</span>promise (fn, context, args)](#apidoc.element.bcrypt.promises.promise)
- description and source-code
```javascript
promise = function (fn, context, args) {

    //can't do anything without Promise so fail silently
    if (typeof Promise === 'undefined') {
        return;
    }

    if (!Array.isArray(args)) {
        args = Array.prototype.slice.call(args);
    }

    if (typeof fn !== 'function') {
        return Promise.reject(new Error('fn must be a function'));
    }

    return new Promise(function(resolve, reject) {
        args.push(function(err, data) {
            if (err) {
                reject(err);
            } else {
                resolve(data);
            }
        });

        fn.apply(context, args);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bcrypt.promises.reject"></a>[function <span class="apidocSignatureSpan">bcrypt.promises.</span>reject (err)](#apidoc.element.bcrypt.promises.reject)
- description and source-code
```javascript
reject = function (err) {

    // silently swallow errors if Promise is not defined
    // emulating old behavior
    if (typeof Promise === 'undefined') {
        return;
    }

    return Promise.reject(err);
}
```
- example usage
```shell
...
}

if (!Array.isArray(args)) {
    args = Array.prototype.slice.call(args);
}

if (typeof fn !== 'function') {
    return Promise.reject(new Error('fn must be a function'));
}

return new Promise(function(resolve, reject) {
    args.push(function(err, data) {
        if (err) {
            reject(err);
        } else {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

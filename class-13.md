[<==Back](README.md)

## What we want

- lots of storage
- on the client's side
- lasting beyond a page refresh
- isnt transmitted to the server

http request containing sensitive data in cookies are transmitted unencrypted over the internet

During the *first great browser wars*

- microsoft invented many things
- of our concern is the internet explorer and DHTML Behaviors

## - userData is our **focus**

Flash *cookies* was invented in 2002 that Local Shared Objects was in

- local shared object allowed Flash to store up to 100 KB of data per domain.

# HTML 5 Storage

- this saves the day

``` javascript

function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}

```


HTML5 storage is based on named key/value pairs.

- Store data on a named key

- retreive data with same key

``` javascript

interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};

var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);

var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;

interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};

interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index);
};
```




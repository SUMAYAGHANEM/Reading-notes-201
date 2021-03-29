#  LOCAL STORAGE FOR WEB APPLICATIONS
1-In the beginning, there was only Internet Explorer,Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars,
Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.

2-user data : allows web pages to store up to 64 KB of data per domain
3-In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment,
the feature is properly known as Local Shared Objects. Briefly, it allows Flash objects to store up to 100 KB of data per domain

4-In the meantime, Brad Neuberg and others continued to hack away on dojox.storage to provide a unified interface to all these different plugins and APIs. By 2009, 
dojox.storage could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5
storage that was only implemented in older versions of Firefox.

![d](https://miro.medium.com/max/2288/1*WVlN_Z4uHPp0IIDrd-b46g.jpeg)

**INTRODUCING HTML5 STORAGE**
a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.

HTML5 STORAGE SUPPORT
:
![dsfsd](https://imgs.developpaper.com/imgs/2885411287-587d9361eda0f_articlex.png)
From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser supports it.

**USING HTML5 STORAGE**
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript,
*needed : 
you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
*wxample :*
interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};

**methods**
removing the value for a given named key, and clearing the entire storage area
interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};

**TRACKING CHANGES TO THE HTML5 STORAGE AREA**
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something

![dsfsg](data:image/png;base64,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)


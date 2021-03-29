#  LOCAL STORAGE FOR WEB APPLICATIONS
1-In the beginning, there was only Internet Explorer,Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars,<P>
Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.<P>

2-user data : allows web pages to store up to 64 KB of data per domain<P>
3-In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment,<P>
the feature is properly known as Local Shared Objects. Briefly, it allows Flash objects to store up to 100 KB of data per domain<P>

4-In the meantime, Brad Neuberg and others continued to hack away on dojox.storage to provide a unified interface to all these different plugins and APIs. By 2009,<P> 
dojox.storage could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5<P>
storage that was only implemented in older versions of Firefox.<P>

![d](https://miro.medium.com/max/2288/1*WVlN_Z4uHPp0IIDrd-b46g.jpeg)<P>

**INTRODUCING HTML5 STORAGE**<P>
a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political <P><P>reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.

HTML5 STORAGE SUPPORT<P>
:
![dsfsd](https://imgs.developpaper.com/imgs/2885411287-587d9361eda0f_articlex.png)<P>
From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser<P> supports it.<P>

**USING HTML5 STORAGE**<P>
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can<P> be any type supported by JavaScript,<P>
*needed : <P>
you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.<P>
*wxample :*<P>
interface Storage {<P>
  getter any getItem(in DOMString key);<P>
  setter creator void setItem(in DOMString key, in any data);<P>
};<P>
<P>
**methods**<P>
removing the value for a given named key, and clearing the entire storage area<P>
interface Storage {<P><P>
  deleter void removeItem(in DOMString key);<P>
  void clear();<P>
};<P><P>

**TRACKING CHANGES TO THE HTML5 STORAGE AREA**<P>
If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(),<P> removeItem(), or clear() is called and actually changes something<P>

![dsfsg](https://i.stack.imgur.com/sMNoo.png)


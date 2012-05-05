yaaw
====

Yet Another Aria2 Web Frontend in pure HTML/CSS/Javascirpt.

No HTTP server, backend or server-side program. All you need is just a browser.


Usage
-----
1. run aria2 with RPC enabled
> aria2c --enable-rpc --rpc-listen-all=true  --rpc-allow-origin-all -c -D
>
> Warning: This options will not verify the identity of caller. KEEP THE ADDRESS SECRET.

2. visit index.html.

3. Change the setting of "JSON-RPC Path" if it's needed.

Components
----------
+ [Bootstrap](http://twitter.github.com/bootstrap/)
+ [mustache.js](https://github.com/janl/mustache.js)
+ [jQuery](http://jquery.com/)
+ [jQuery Storage](http://archive.plugins.jquery.com/project/html5Storage)
+ [JSON RPC 2.0 jQuery Plugin](https://github.com/datagraph/jquery-jsonrpc)

License
-------
yaaw is licensed under GUN Lesser General Public License.
You may get a copy of the GUN Lesser General Public License from http://www.gnu.org/licenses/lgpl.txt


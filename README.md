node-red-contrib-ivona-tts
==============================

<a href="http://nodered.org" target="_new">Node-RED</a> node that connects to <a href="http://www.ivona.com/" target="_new">Ivona</a>.

Install
-------

Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install node-red-contrib-ivona-tts

Credentials
-----------

You can register and create IVONA Speech Cloud API credentials here: <a href="http://developer.ivona.com/en/speechcloud/index.html" target="_new">Ivona For Developers</a>.

Usage
-----

TBD

Acknowledgements
==============================

Uses <a href="https://github.com/tmanderson" target="_new">tmanderson</a> NodeJS Ivona Cloud implementation <a href="https://github.com/tmanderson/ivona-node" target="_new">https://github.com/tmanderson/ivona-node</a>.

Inspired by the Ivona node by <a href="https://github.com/Baael" target="_new">Baael</a>: <a href="https://github.com/Baael/wojak-nodes/tree/master/node-red-contrib-ivona-tts" target="_new">https://github.com/Baael/wojak-nodes/tree/master/node-red-contrib-ivona-tts</a>.

TODO
=====

Improvements and bugs related to ivona-node should be fixed in https://github.com/technocreatives/ivona-node and then pull requested to https://github.com/tmanderson/ivona-node. If not approved we need to make a new NPM module with out fork and depend on that one instead.

- BUG: not calling on error when authentication fails (wrong access and/or secret keys). 




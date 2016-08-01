learn-websockets-over-rabbitmq
==============================

Requirements
------------

* rabbitmq
* rabbitmq stomp plugin

Running the project
-------------------

::

    python -m SimpleHTTPServer 9000

And head to http://127.0.0.1:9000

You should now see a sample message delivered to `ws_in` queue.

To receive messages over WS just put them into the `ws_out` queue and in a fraction of a second you should be able to
see that in your browser.

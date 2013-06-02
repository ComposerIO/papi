**[Composer.io](http://composer.io)** is a website that lets you post status updates to many social networks at once.


Ping api
===

The Composer.io Ping API is becoming a ping.fm drop in replacement.

The currently implemented methods are:
* user.services
* user.key
* user.latest
* user.post

It's been lightly tested with WePing and Pingdroid (using a hosts file hack) and has been used successfully with both clients.

The API host is **http://papi.cmp.sr/** (this is an identical number of characters as api.ping.fm,
so you could try to hack binary Ping FM code to work with Composer).

In the future we might have a more modern API at api.cmp.sr.

Questions
------

* What are triggers? How did they work?


Clients
------

* https://code.google.com/p/pingboard/
* https://code.google.com/p/pingr/
* http://www.splitbrain.org/blog/2010-02/11-weping_a_multi_user_ping.fm_client

Plugins
--------
* Pidgin http://code.google.com/p/pidgin-ping/
* WordPress https://code.google.com/p/publish2pingfm/
* Joomla https://code.google.com/p/plg-pingfm/
* ActionScript https://code.google.com/p/as3pingfm/

### Drupal ###
https://drupal.org/project/pingfm
Issue: https://drupal.org/node/1678004

Libraries
---------

https://github.com/Oshuma/pingfm
has some tests: https://github.com/Oshuma/pingfm/blob/master/spec/pingfm/client_spec.rb

https://code.google.com/p/pyngfm/
see also http://technicae.cogitat.io/2009/09/twisted-pingfm-client.html

Find more ping.fm code
---------------------------
https://code.google.com/query/#q=ping%20fm




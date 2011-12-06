# Octopress Flickr Aside

This is a simple aside for <a href="http://www.octopress.org">Octopress</a> that uses Flickr API to pull your most recent shots from your photostream.

It was greatly inspired by <a href="https://gist.github.com/1421792">Gist 1421792</a> that insert a Flickr banner in the sidebar.

## How to use it

First of all you need to copy *flickr.html* into your octopress installation in the directory *source/_includes/custom/asides*.
Then you need to update the _config.yml file:

* add *'custom/asides/flickr.html'* to *default_asides*
* add flickr settings at the end of the file:

```
flickr_userid: your_user_id
flickr_nickname: your_nickname
flickr_apikey: your_apikey
flickr_count: 5
```

You can get your Flickr userId using <a href="http://idgettr.com/">idgettr</a>, while for the apikey you must visit <a href="http://www.flickr.com/services/api/keys/"> http://www.flickr.com/services/api/keys/</a> while logged in on Flickr and generate a new Api key.

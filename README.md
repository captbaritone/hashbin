# HashB.in

HashB.in is a paste bin that avoids knowledge of the contents of its pastes.

## How?

There are two tricks employed here.

1. The entire contents of the paste are encoded in the URL. This means we are
   not storing the content of the paste on our server. Instead, the source
   providing the link is supplying the content.

2. We store this encoded content in the hash of the URL. This segment of the
   URL has the unique property of not being sent to the server.

## Doesn't this make the URL's super long?

Yes. However, in this age of URL shorteners, this is increasingly not
a problem.

## Credit

This site was inspired by two other very similar sites:

- http://iamnotagoodartist.com/web/an-auto-updating-data-uri-text-editor/
- [Hashify.me](http://bit.ly/dXYxGU)

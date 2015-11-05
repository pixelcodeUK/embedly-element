# embedly-element

An element for embedding websites using the Embed.ly service.

# Examples

Basic example of embedding a tweet:

``
<embedly-element url="https://twitter.com/jack/status/20" link-text="Tweet"></embedly-element>
``

Show extra social sharing options:

``
<embedly-element url="https://twitter.com/jack/status/20" link-text="Tweet" show-controls></embedly-element>
``

Show extra sharing chrome:

``
<embedly-element url="https://twitter.com/jack/status/20" link-text="Tweet" show-chrome></embedly-element>
``

Align embed right and use dark theme:

``
<embedly-element url="https://twitter.com/jack/status/20" link-text="Tweet" theme="dark" align="right"></embedly-element>
``

Set a manual width:

``
<embedly-element url="https://twitter.com/jack/status/20" link-text="Tweet" width="200"></embedly-element>
``

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

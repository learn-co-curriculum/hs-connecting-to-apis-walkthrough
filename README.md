

### Learning to Use APIs

APIs are all different, but follow similar conventions. They receive instructions via a URL post request and return data in the form of an XML or JSON hash. Luckily, there are several ruby gems that make this easier. Here's a little guide to figuring out APIs. Note that getting APIs to work will require patience and persistence - it's a matter of trial and error!

+ Find out if an API exists for the application you're trying to connect to.
+ If it exists, look for a ruby gem for that API. For example, (https://github.com/sferik/twitter)
+ `gem install` the gem and `require` the gem in your application.
+ Register with the API's provider so that you can authenticate and use their API!
+ **Read the documentation!!!!** This is the most important part. Since every API is different, you need to get to know the specific gem's functionality and figure out how to integrate the api.
+ In most cases, you'll want to integrate your API in as an object oriented class, so that it can be extended and modified easily in your code.


<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-connecting-to-apis-walkthrough' title='Learning to Use APIs'>Learning to Use APIs</a> on Learn.co and start learning to code for free.</p>

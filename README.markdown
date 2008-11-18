### What is it? ###

Sinatra ruby server implementing QBWC callbacks in < 75 LOC

### Introduction ###

I've blogged extensively on QuickBooks integration in Rails on my blog [Depixelate](http://depixelate.com).

The short story is that working with ActionWebService sucks.

mini-qbwc is an experiment in simplicity and non-suckiness.

### Setup ###

1) Install sinatra
  
    $ sudo gem install sinatra
    
2) Start server

    $ ruby qbwc.rb
    
3) Install app.qwc in QBWC and run sync
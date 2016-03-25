## Twitter Bot
### SDRuby Magic Night March 24, 2016

![Twitter XKCD](http://imgs.xkcd.com/comics/twitter_bot.png)

This month's challenge is to create a program that will generate messages 140
characters in length. There primary use will be to create a Twitter
“personality”. At the end of the night these “personalities” will be
unleashed on the internet and we’ll see how they do in the wild. The
“personality” component can take any inputs and will produce a 140 character
message when called. The “personality” may remember state.


This challenge has several "levels", see how many you can complete:

1) Create a simple bot that responds to messages at the command line and
produces 140 or less character response

2) Setup a twitter account and use the API to post responses.

3) Deploy your application to heroku or other service so that your bot can stay
live 24/7.

4) Expand the range and "intelligence" of your bot, see resources below.


Some notes on integrating with twitter:

You will likely need four pieces of auth data a twitter consumer key&secret and
a twitter authorization token&secret, this comes from creating a
twitter app at: [https://dev.twitter.com/](https://dev.twitter.com/).

If you create your bot's twitter account, and then use that account to create
the twitter app you can keep all of these details off your main twitter account
and in one place. See the ruby gem docs for how to use these auth data pieces:
[http://www.rubydoc.info/gems/twitter](http://www.rubydoc.info/gems/twitter)

Resources of note:

- [Twitter dev](https://dev.twitter.com/)
- [Twitter gem](https://github.com/sferik/twitter)
- [Twitter Bot rules](https://support.twitter.com/articles/76915)
- [Twitter API rules](https://support.twitter.com/articles/160385)
- [Markov chains](https://en.wikipedia.org/wiki/Markov_chain)
- [Markov chains explained visually](http://setosa.io/ev/markov-chains/)
- [TwitterBot wikipedia](https://en.wikipedia.org/wiki/Twitterbot)


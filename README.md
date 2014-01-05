Lyricize
==============

Lyricize creates "new" song lyrics based on a supplied artist or band name using a [Markov chain](https://github.com/MaxWagner/PyMarkovChain/) and API calls to a [lyrics database](http://www.lyricsnmusic.com/api).

This is a short Flask app that has beed [deployed on Heroku](). To run it locally yourself, you will need to supply a *.env* file with the following two variables:

	SECRET_KEY=XXXXXXXX
	API_KEY=XXXXXXXX

The SECRET_KEY is a random string used by Flask, while the API_KEY can be obtained from [lyricsnmusic.com/api_keys/new](http://www.lyricsnmusic.com/api_keys/new).

You may also provide a PORT number or use the default of 5000. To deploy and run on Heroku, just set SECRET_KEY and API_KEY as Heroku [config vars](https://devcenter.heroku.com/articles/config-vars).
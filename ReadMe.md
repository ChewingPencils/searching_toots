# Using Tweetbot Searches to Replace RSS

Here are a few examples of how I've replaces RSS with Twitter.

Any of these can be easyily modified to work with Drafts or Launch Center Pro on iOS.


## Work Related Searches
	
### Crypto

**query**
:	filter:links -filter:mentions -filter:retweets lang:en -"RT " #crypto OR #cryptography OR crypto OR cryptography 

`tweetbot:///search?query=filter%3Alinks%20-filter%3Amentions%20-filter%3Aretweets%20lang%3Aen%20-%22RT%20%22%20%23crypto%20OR%20%23cryptography%20OR%20crypto%20OR%20cryptography%20{query}`
	
### Security

#### Security Open

**query**
:	filter:links -filter:mentions -filter:retweets lang:en -"RT " #security OR #privacy OR #infosec OR security OR vulnerability -"security force"

`tweetbot:///search?query=filter%3Alinks%20-filter%3Amentions%20-filter%3Aretweets%20lang%3Aen%20-%22RT%20%22%20%23security%20OR%20%23privacy%20OR%20%23infosec%20OR%20security%20OR%20vulnerability%20-%22security%20force%22`

#### Security Focused

**query**
:	#security OR #privacy OR #infosec filter:links -filter:mentions -filter:retweets lang:en -"RT " 

`tweetbot:///search?query=%23security%20OR%20%23privacy%20OR%20%23infosec%20filter%3Alinks%20-filter%3Amentions%20-filter%3Aretweets%20lang%3Aen%20-%22RT%20%22%20{query}`

## Personal

### Get Links From A Specific User
	
**query**
:	filter:links -filter:mentions -filter:retweets lang:en -"RT " from:{query}
	
`tweetbot:///search?query=filter%3Alinks%20-filter%3Amentions%20-filter%3Aretweets%20lang%3Aen%20-%22RT%20%22%20from%3A{query}`
	
### Example: Links From A Group of Users

**query**
:	from:macdrifter OR from:viticci OR from:jasonschreier OR from:tinycartridge OR from:gamespite OR from:patrickklepek OR from:jcfletcher OR from:shmups filter:links -filter:mentions -filter:retweets lang:en {query}
	
`tweetbot:///search?query=from%3Amacdrifter%20OR%20from%3Aviticci%20OR%20from%3Ajasonschreier%20OR%20from%3Atinycartridge%20OR%20from%3Agamespite%20OR%20from%3Apatrickklepek%20OR%20from%3Ajcfletcher%20OR%20from%3Ashmups%20filter%3Alinks%20-filter%3Amentions%20-filter%3Aretweets%20lang%3Aen%20{query}`

I have several queries that group toghther simmilar news sources or Twitter users.
	

	
	
	
	

Hashtag entered and searched
		|
		|
		|
		V
Make call to REST client stored on server
		|
		|
		|
		V
REST client pulls data in JSON. Formats JSON,
meaning it ensures the first instance is sent back
first. (At later expansions to the project,
it will pull more than just the first instance)
		|
		|
		|
		V
Sends back HTTP Response containing JSON data about
first tweet.
# wikiPlug
wikiPlug is a Beets plugin which is written in Python 3.4.4 to collect the metadata of tracks and albums from Wikipedia.

Wikipedia serves as an online resource that is defined as a free library and kept by the user as input for information on each subject. When music is approached as its metadata, it can be said that a large number of users and writers may be one of the right sources for acquiring this platform’s personal information in the future, even though it does not contain as many accurate and numerous metadata as the competent and approved platforms such as Discogs, MusicBrainz and Beatport. 
 
Within this Project, a Beets plugin was developed that edits tag information for music catalogs and corrects missing or incomplete tag information. The developed plugin uses Wikipedia as a metadata source and obtains metadata with HTML parsing by retrieving this content after accessing the URL created in the plugin with the title and album title of the musical material in order to use the desired tag information on platform. The resulting metadata is processed into the Beets database once user approval is obtained and processed through Beets on the existing material. 
 
wikiPlug is being run on the Python path, and besides the musicBrainz metadata search that Beets has, it provides the user with the Wikipedia metadata as auto-tagger. 

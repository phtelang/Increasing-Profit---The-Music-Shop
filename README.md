## Increasing Profit : The Music Shop

I worked with the Chinook database. It contains information about a fictional digital music shop - kind of like a mini-iTunes store. The Chinook database contains information about the artists, songs, and albums from the music shop, as well as information on the shop's employees, customers, and the customers purchases. The database and the schema diagram are available here.

Below questions were explored to help business take decisions and increase profit:

Which new albums should be considered for purchase from the US genre to increase profit?
How are employees performing?
Which countries have good opportunity for sales?
Should more albums be purchased instead of individual tracks?
Which artists are used the most in playlists? Which are the highest selling artists in US?
How many tracks have been purchased atleast once?
What is the range of tracks in the store and their sales popularity?
How does popularity vary for protected vs non-protected media types?
Summary of Results
Analyzing US genre sales, new albums by Red Tone (Punk), Slim Jim Bites (Blues) and Meteor and the Girls (Pop) should be purchased. Rock and Latin can be considered for future purchases because of high popularity.
While there is a 20% difference in sales between Jane (the top employee) and Steve (the bottom employee), the difference roughly corresponds with the differences in their hiring dates.
Czech Republic, USA and India have good opportunity for sales. As the sample size is not large enough to give us high confidence, starting off with small campaigns in these countries, collecting and analyzing the new customers to make sure that these trends hold with new customers would be a good idea.
Album purchases is recommended instead of purchasing only select tracks from albums.
Iron Maiden is by far the most popular artist in playlists and has the maximum number of purchases.
56.63% of tracks have been purchased at least once.
The available range of tracks is not closely reflective of popularity. There are more tracks of Latin and Rock music than it can sell. It is recommended to look into the selections of tracks in these particular types as some of the currect selections are not popular with the customer.
Unprotected media types sell more than protected media types.
To view the code and graphs accurately, please click on this link as some of the Plotly graphs are not displayed directly on Github.

Installation
Download the source database on your local folder.
Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
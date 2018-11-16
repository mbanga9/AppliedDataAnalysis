# AppliedDataAnalysis

Take a look at the nbviewer version to vizualize the results:

-----------------------------------------------------------------------------
http://nbviewer.jupyter.org/gist/mbanga9/8898bb8758589fb5c3be4b282b56cb91
-----------------------------------------------------------------------------


# Title
Evolution of Direct Democracy in Switzerland

# Abstract
Our project follows this central question about democracy in Switzerland.
Our primary data source for this are the archives of the Swiss newspaper 'Le Temps',
which regroups data from three different newspapers from the past 200 years.
I wish to see what kind of patterns can be noticed that surround Swiss voting
themes of the past and the present. Are we continuously voting on the same questions?
Do our answers to these questions change? What about entirely new themes? In
the last 200 years, life in Switzerland has radically changed, I would expect
this to be reflected in the topics that have been voted on. Especially with
regards to technological development and social norms. How has the voting
process been used to bring in these new changes under Swiss law?
While the archives from 'Le Temps' will serve as our reference, I will try to
make a comparison with present day trends using the Swiss tweets dataset.

# Research questions
* Do we have the freedom to vote on any question we wish?
* Do the same votations, or topics, keep coming up? Is this throughout history
or during specific periods?
* Are the results of these repeated votations changing throughout time?
* Can we link big changes in technological and societal norms to previous votations?
* How has direct democracy been used? Is it increasing or decreasing? What kind
of votations is it used for?

# Dataset
The main dataset used are the archives Le Temps. After talking with
Giovanni I understand that these will be available on the cluster in a
processed from, with the articles available as strings and images. Although
the archives are enormous, I will only make use of a relatively small percentage
of them that are related to voting. The raw data mining part of this project
will be related to string handling and processing. As the articles are already
available in text form there is no need for data extraction on the raw images
from the newspapers. It is important to access and use the cluster in an 
appropriate way. That is, how to query archives and sort them.

The secondary dataset is the collection of Swiss tweets. I'll also
be performing similar string handling and processing as previously described. 
There will be additional processing of metadata associated with these tweets,
primarily the geolocation of some of these tweets.


The use of the cluster appers mandatory to speed up drastically the computation
time and get results in a reasonable amout of time. It's important to note that
We are working with a 10GB dataset.

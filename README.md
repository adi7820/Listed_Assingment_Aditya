# Listed_Assingment_Aditya

### Problem Statement:
The assignment requires fetching YouTube channels by performing a Google search for 'openinapp.co'.

```python
from googlesearch import search
```
The task involves searching the given query on Google and storing the resulting links in a list.

It can be installed using pip: 
```python 
!pip install googlesearch-python
```
#### execute_youtube_search(query,max_results)
The above function in the code requires two parameters: a query and `max_results`, which determines the maximum number of search results to retrieve. The function then modifies the input query to specifically fetch YouTube channels, as per the requirements of the assignment. Additionally, it excludes channels with the term 'community' since they typically contain short videos from individuals rather than full-fledged channels.

Finally, the function saves the resulting YouTube channel links in a file named 'youtube_links.csv'. This file contains all the links to the YouTube channels based on the provided search query.

#### You can find the results in the uploaded video.

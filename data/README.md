# SISE2601 Project data description
================
Team O - Omer Gazit and Ido Bouhnik 

This Markdown file describes the data folder structure and organization ...

data_change.csv - contain the search result sites and manual ranking of the google search results.
fields:
  topic - the Google search term (English) 
	language - the search language 
	url - the result website url 
	title - the search result url name 
# ranking system
	definition - how easy was to find the term definition on the site : 
		0 - not found at all
        	1 - definithion to related subject
		2 - found but not immediately
		3 - found very easily 
	information - how mach information was found about the topic on the site :
		0 - not relevant information 
		1 - not academic articles site 
        	2 - related information and References
		3 - a lot of information and References about the subject
	visualization - is there a visualization related to the term :
		0 - no visualization at all
		1 - 1 or 2  visualizations
		2 - 3-5 visualizations
        	3 - 6 or more 
	site quality - How much is invested in the site :
		1 - amateur site 
		2 - medium 
		3 - professional website
	adds - is the site advertising something? (1 - Yes or 0 - No filed) 

html_classifire.csv - csv file that hold paths to local html files of google search.

Result_num_changed.csv - hold the number of result for every Google search 


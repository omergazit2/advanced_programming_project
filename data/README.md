# SISE2601 Project data description
================
Team O - Omer Gazit and Ido Bouhnik 

This Markdown file describes the data folder structure and organization ...


searching_for_science diractory - contain all the json and html file from google serches

search_data.csv - contain the number of result and result time for each google search 

term_classified.csv - contain for each termID its english name and classification 
	class 1 - contemporary term 
	class 2 - non-contemporary term

result_data.csv - contain the position and the link for every google serch

Result_num_changed.csv - hold the number of result for every Google search 

top3_edited.csv - contain quality ranking for each 3 firs google search result by the next ranking system: 

| rank  | definition | information | visualization  | site quality  | adds - Boolean |
| :------------ |:---------------:| -----:|:------------ |:---------------:| -----:|
| 0 | no definition at all | no relevant information |no visualization at all      | no illustrations | No |
| 1 | Partial definition or requires search |   Contains advertising information on a related topic |1 or 2  ilustrations      |   amateur website       |   Yes |
| 2 | found but not immediately  |   Subject information without link to relevent reading |3-5 ilustrations | medium quality website     |    -- |
| 3 | well define and easy to find |    Subject information with link to relevent reading |6 or more ilustrations or vidio | professional website        |    -- |

wikipidia_DF.csv - contain the scraping metadata from wikipedia serch
	img-num: number of images on page 
	sections: number of sub-titles on page 
	references: number of links to other subjects
	word_count: leangth of the text
	term_appirance: number of appirance of the search word in the text
	text: the scraped wikipedia text
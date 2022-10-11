
Data description for Meetup tag dataset.

1. tag_text.csv stores the tag_id and real tag text mapping. The csv file has
  two columns, first is tag_id and the second is the corrsponding tag's text.
  E.g. "16,sales".

2. user_tag.csv.zip (compressed in zip) stores the tags selected by each user. The csv file contains
  two columns, which are user_id and tag_id, respectively. E.g. a line
  "1,12" represents user "1" is interested in tag id "12".

3. group_tag.csv stores the tags selected by online social groups. Similarly, 
  "1,606" represents group "1" is interested in tag id "606".


Data description for Meetup online/offline social network dataset.

1. user_group.csv: represents the online social connections. Meetup allow users
  to form online social groups. Thus this file stores information for online
  group membership between user and group. The file is a csv file with two
  columns (user_id and group_id).
  E.g. a line "14,145" means user "14" participated the group "145".

2. user_event-0.csv.zip user_event-1.zip (split as it exceed 100MB even in compressed format):
  represents the offline social connections. In meetup.com,
  users create offline social events (face-to-face meetups). Therefore, this
  file contains information about offline social event participations. The two
  columns in the csv file contain mapping between user_id and event
  participated by him. E.g. a line "10,15" represents user "10" participated
  the event "15".

3. event_group.csv.zip (compressed in zip): demonstrates the event and its hosting group. In meetup.com,
  group may host an social event. This event hosting group information was not
  studied in our KDD2012 paper.



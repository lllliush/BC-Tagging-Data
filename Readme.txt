This repository provides the research data for our paper "Tagging Items Automatically Based on Both Content Information and Browsing Behaviors".

It has three types of data:
- word.data
This file contains the content information of each app, where each line represents an app:
app_id{\t}[word_id:word_counts ]*

- neighbor_[n].data (where [n] represents the time gap threshold for extracting the neighbors, e.g. neighbor_60.data means the time gap threshold is 60s)
This file contains the neighbor information of each app, where each line represents an app:
app_id{\t}[neighbor_app_id:neighbor_counts ]*

- tag.data
This file contains the tags that are manually assigned to each app, where each line represents an app_id{\t}[tag_id ]*

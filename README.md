# New York Times Top 100 Articles a Week

Combines public New York Times RSS feeds into one feed, with the goal of
surfacing only the top items.

Aggregated feed: https://s3-us-west-2.amazonaws.com/rsscombine/new-york-times-rss-top-100.xml

## Guidelines

As pull requests are merged and this README is updated, the aggregated feed will automatically update.

## RSS Feeds

  - https://www.google.com/alerts/feeds/15349801374406371600/3020644589033681842
  - https://www.google.com/alerts/feeds/15349801374406371600/3671298862525163557
  - https://www.google.com/alerts/feeds/15349801374406371600/610144525991812452
  - https://www.google.com/alerts/feeds/15349801374406371600/821885301883673074
  - https://www.google.com/alerts/feeds/15349801374406371600/16317114205743916924
  - https://www.google.com/alerts/feeds/15349801374406371600/1621023483551191395
  - https://www.google.com/alerts/feeds/15349801374406371600/3743077714605075672
  - https://www.google.com/alerts/feeds/15349801374406371600/247268169075390418
  - https://www.google.com/alerts/feeds/15349801374406371600/9651913786136382006
  - https://www.google.com/alerts/feeds/15349801374406371600/6496764911669033061
  - https://www.google.com/alerts/feeds/15349801374406371600/8818163910002940090
  - https://www.google.com/alerts/feeds/15349801374406371600/14656916877071299461

## Technical Details

The code that does the aggregation is here: https://github.com/chase-seibert/rsscombine

There is a cache timeout of one hour on adding new feeds, and updating feeds.

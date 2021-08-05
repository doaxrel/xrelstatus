---
title: Scheduled Updates

draft: false

date: 2021-08-05 17:33:00

# Status: "resolved" | "in_progress" | "scheduled"
status: "resolved"

# This message will be taken out of the flow of events
# and displayed at top of page or below the header
# as long as its status is marked as in_progress
# pinned: (empty) | top | belowheader
pinned: 

# Duration for "scheduled" issues: Raw text, ie 5mn, 1h, 1 hour,..
duration: 1h

# Max severity: will be displayed when issue is resolved, in the past events section
# Max_severity: ok | disrupted | down | monitoring | maintenance
max_severity: maintenance

# Current severity: used for current issue display
# current_severity: ok | disrupted | down | monitoring | maintenance
current_severity: ok

# Full date: 2019-03-29 17:26:09
 resolved_on: 2021-08-05 18:15:00

# Affected components, must use exact names defined in site config
affected:
  - Website
  - API

twitterFeed:
enableComments: false

## Do not change
section: issue

# Short code available in content to display current date
# in a short format. For instance for issue updates.

# {{< track "2019-03-26 15:31:06" >}}
# {{< track "" >}}

## Enter below issue description and subsequent updates if any
---
**Scheduled maintenace:** Servers are down while we do some maintenance.
\

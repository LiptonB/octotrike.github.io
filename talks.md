---
title: Talks
description: Abstracts and slides from public talks about the Trike tool or threat modeling methodology.
---

# Upcoming Talks
We have no public talks about Trike scheduled in the near future.

# Past Talks
{% for talk in site.talks %}
* {{ talk.date | date_to_string }} - [{{ talk.name }}]({{ talk.url }}) @ [{{ talk.venue }}]({{ talk.venueurl }})
{% endfor %}

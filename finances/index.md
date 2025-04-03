---
layout: page
title: Guild Finances
---

# Guild Finances

## Current Balance
As of April 2024: 2000pp

## Monthly Statements

{% for post in site.posts %}
  {% if post.tags contains 'finances' %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%B %Y" }}
{{ post.excerpt }}
  {% endif %}
{% endfor %}

## Financial Summary
* Starting Balance: 1500pp
* Total Donations: 1000pp
* Total Expenses: 500pp
* Ending Balance: 2000pp

## Previous Statements
* [March 2024](/finances/2024-03-01-march-statement)
* [February 2024](/finances/2024-02-01-february-statement)
* [January 2024](/finances/2024-01-01-january-statement) 
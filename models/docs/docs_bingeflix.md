# Bingeflix Docs
This file contains docs blocks for Bingeflix sources

## Users
This section contains documentation from the Bingeflix Users table.

{% docs bingeflix_user_id %}
The unique identifier of the Bingeflix user.
{% enddocs %}

## Events
{% docs table_events %} 
Contains events taken by users on the Bingeflix platform. Each record represents a unique action performed by a unique user.
{% enddocs %}

{% docs session_id %} 
Identifier for unique session associated with a user at a particular point in time.
{% enddocs %}

{% docs event_created_at %} 
The time and date the event occurred.
{% enddocs %}

{% docs event_name %} 
The type of event that occurred.
{% enddocs %}

{% docs event_id %} 
Identifier for unique event associated with a user at a particular point in time.
{% enddocs
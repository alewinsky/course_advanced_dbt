# Bingeflix Docs
This file contains docs blocks for Bingeflix sources

## Subscriptions
This section contains documentation from the Bingeflix Subscriptions table.

{% docs subscription_id %}
The unique identifier of the subscription.
{% enddocs %}

{% docs subscription_plan_id %}
The subscription plan identifier.
{% enddocs %}

{% docs subscription_starts_at %}
When the subscription started.
{% enddocs %}

{% docs subscription_ends_at %}
When the subscription ended. This value is NULL if the subscription is active.
{% enddocs %}

{% docs subscription_plan_name %}
The type of the subsciption plan.
{% enddocs %}

{% docs subscription_pricing %}
The monthly cost of the subscription.
{% enddocs %}

{% docs subscription_billing_period %}
The cadence of the billing period.
{% enddocs %}

## Users
This section contains documentation from the Bingeflix Users table.

{% docs bingeflix_user_id %}
The unique identifier of the Bingeflix user on the Bingeflix application.
{% enddocs %}

## Events
This section contains documentation from the Bingeflix Events table.

{% docs table_events %} 
Contains events taken by users on the Bingeflix platform. Each record represents a unique action performed by a unique user.
{% enddocs %}

{% docs session_id %} 
Identifier for unique session associated with a user at the specific timedate.
{% enddocs %}

{% docs event_created_at %} 
The time and date the event occurred.
{% enddocs %}

{% docs event_name %} 
The type of event that occurred.
{% enddocs %}

{% docs event_id %} 
Identifier for a unique event associated with a user at a specific timedate.
{% enddocs %}
---
layout: default
permalink: /plan/
---

{:refdef: style="text-align: center;"}
![Project architecture]({{site.url}}/assets/architecture.png)
{:refdef}

Our software stack consists of REST API, using [Django REST Framework](http://www.django-rest-framework.org/), web frontend using [ReactJS](https://reactjs.org/) and SQL Server Database.
Most of our backend API services are implemented in Python, which then auto-generates SQL query to our SQL server.

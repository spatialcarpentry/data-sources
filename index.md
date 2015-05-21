---
layout: page
title: Data Sources
tagline: Repository of data sources
---
{% include JB/setup %}

This is a repository of data sources available on the internet. These include FTP sites and may require some understanding of the FTP site structure and data naming conventions.

The user is responsible for data manipulation and formatting.

Be sure to understand the data by reading the documentation or metadata. Some sites contain multiple directories or versions of data, it's highly advised to view README files or documentation within these directories.

Sources will continue to be added.

### Sources:

<ol class="lessons">
{% for post in site.posts %}
<li><a href="{{BASE_PATH}}{{post.url}}">{{ post.title}}</a></li>
</ol>
{% endfor %}

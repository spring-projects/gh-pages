---
layout: base_layout
title: Spring Project Title

badges:
  - name: CI (Bamboo)
    image_url: http://marketplace.servicerocket.com/static/products/atlassian/atlassian-bamboo-logo.png
    url:  https://ci.spring.io/browse/SPRINGDATAJPA

  - name: Source (GitHub)
    image_url: https://github.global.ssl.fastly.net/images/modules/logos_page/GitHub-Mark.png
    url:  https://github.com/spring-projects/spring-data-jpa

  - name: Issues (JIRA)
    image_url: http://redmine-solutions.com/assets/images/jira-logo.png
    url:  https://github.com/spring-projects/spring-data-jpa

  - name: Forum (vBulletin)
    image_url: http://farm8.staticflickr.com/7020/6672142779_a1c3ac2721.jpg
    url:  http://forum.spring.io/forum/spring-projects/data

  - name: StackOverflow
    image_url: http://myrrix.com/wp-content/uploads/2012/06/stackoverflow.png
    url:  http://so.com/questions/tagged/spring-data-jpa

  - name: Metrics (SonarQube)
    image_url: https://2.gravatar.com/avatar/61bb6bd5e640415490ef28e5fdcc746f?d=https%3A%2F%2Fidenticons.github.com%2Fb6100dcb8d05f7c0a9b28633c75fa606.png&s=420
    url:  https://sonar.springsource.org/dashboard/index/org.springframework.data:spring-data-jpa

  - name: Twitter
    image_url: http://www.health2con.com/events/files/twitter-logo-square-150x150.png
    url:  https://twitter.com/SpringData


---

<!-- Specify the parent of this project (or delete if none) to influence the rendering of the breadcrumb -->
{% capture parent_link %}
[Spring Parent]({{ site.projects_site_url }}/spring-parent)
{% endcapture %}


{% capture billboard_description %}

**PROJECT DESCRIPTION** Corpus callosum,
[the carbon](#) in our apple pies a mote of dust suspended in a
sunbeam. Muse about! Venture galaxies a billion trillion extraordinary
claims require extraordinary evidence, consciousness a mote of dust
suspended in a sunbeam Apollonius of [Perga Euclid](#) inconspicuous
motes of rock and gas made in the interiors of collapsing stars.

{% endcapture %}

{% capture main_content %}

**INTRODUCTORY PARAGRAPHS** Birth, a very small stage in a vast cosmic
arena extraordinary claims require extraordinary evidence! Flatland
Apollonius of Perga culture inconspicuous motes of rock and gas realm
of the galaxies quasar, corpus callosum, galaxies Drake Equation ship
of the imagination Jean-François Champollion. Galaxies Hypatia!
Trillion tingling of the spine the only home we've ever known
extraordinary claims require extraordinary evidence stirred by
starlight, culture? Flatland Tunguska event finite but unbounded
corpus callosum!

{% include download_widget.md %}

Radio telescope Orion's sword science, brain is the seed of intelligence. Hearts of the stars a still more glorious dawn awaits, how far away tendrils of gossamer clouds with pretty stories for which there's little good evidence!

Intelligent beings are creatures of the cosmos at the edge of forever of brilliant syntheses network of wormholes tingling of the spine not a sunrise but a galaxyrise prime number Vangelis gathered by gravity Orion's sword network of wormholes rogue tingling of the spine?

## Features

* Implementation of CRUD methods for JPA Entities
* Dynamic query generation from query method names
* Transparent triggering of JPA NamedQueries by query methods
* Implementation domain base classes providing basic properties
* Support for transparent auditing (created, last changed)
* Possibility to integrate custom repository code
* Easy Spring integration with custom namespace

```java
public static void main(){
	foo();
}
```

{% endcapture %}

{% capture related_resources %}

### Spring Sample Projects

* [Project Name 1](#)
* [Project name 2](#)
* [Project name nth](#)

### Getting Started Guides

* [Getting Started Guide 1]({{site.main_site_url}}/gs-rest-service)
* [Getting Started Guide 2]({{site.main_site_url}}/gs-rest-service)
* [Getting Started Guide nth]({{site.main_site_url}}/gs-rest-service)

### Tutorials

* [Tutorial 1](#)
* [Tutorial 2](#)
* [Tutorial nth](#)

{% endcapture %}


{% include project_home_include.md parent_link=parent_link billboard_description=billboard_description main_content=main_content related_resources=related_resources %}

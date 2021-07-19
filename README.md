# Perch-to-Kirby
 
## Overview of terms

| Perch        | Kirby           | more information |  
| ------------- |:-------------:|  -------------:|  
| mysite.com/perch | mysite.com/panel | |  
| Page Properties | make a page tab in the panel  | [tabs in panel](https://getkirby.com/docs/guide/blueprints/tabs) |
|  `\<?php perch_layout('header');?>` | `\<?php snippet('header') ?>` | [snippet](https://getkirby.com/docs/guide/templates/snippets)|
| Page template | 1. In a [blueprint](https://getkirby.com/docs/guide/blueprints/introduction) of the page, for the data definition and panel appearence | 2. In a [page template](https://getkirby.com/docs/guide/templates/basics) for the frontend website |  
| update by replacing /core/ | update by replacing /kirby/ | [update kirby](https://getkirby.com/docs/guide/quickstart#updates) |



## Data model 

**Perch datamodel**  
The definition of the data, the presentation of the field in Perch editor and the frontend presentation of this fields content is all defined in one place: in the content template.
The data is stored in a mySQL database.

**Kirby datamodel**  
The definition of the data as well as the presentation in the Kirby Panel is defined in [blueprints](https://getkirby.com/docs/guide/blueprints/introduction).

The website HTML is defined in [page templates](https://getkirby.com/docs/guide/templates/basics).

The data is stored in text files.
It is possible to only define the blueprint for a page and fill in the data textfile by hand to make the website page appear. If you don't want to use the Panel you dont have to.
This makes it possible to easily fill the initial site with existing data.   





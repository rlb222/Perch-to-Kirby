# Perch-to-Kirby
 
## Overview of terms

| Perch        | Kirby           | more information |  
| ------------- |:-------------:|  -------------:|  
| mysite.com/perch | mysite.com/panel | |  
| Page Properties | make a page tab in the panel  | [tabs in panel](https://getkirby.com/docs/guide/blueprints/tabs) |
|  \<?php perch_layout('header');?> | \<?php snippet('header') ?> | [snippet](https://getkirby.com/docs/guide/templates/snippets)|



## Data model 

**Perch datamodel**  
In Perch the data model is defined in the template. Add some fields to the content template, opening the editpage of the content will cause Perch to add the fields into the database.

The definition of the data, the presentation of the field in Perch editor and the frontend presentation of this fields content is all defined in one place: in the content template.

The data is stored in a mySQL database.

**Kirby datamodel**  
The definition of the data as well as the presentation in the Kirby Panel is stated in blueprints. 




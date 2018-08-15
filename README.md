# foweyarttrail.github.io


Controls the website for foweyarttrail.com:

All content is autogenerated using the files in the `_stops` folder

## What a stop looks like
```
---
layout: stop
title: 10 Station Road
latitude: 50.3395931
longitude: -4.634017
number: 17
hours: 10am - 5pm 17th-19th May or by appt
other: guide dogs only
icons:
  - accessible
image: images/150x150.png
exhibitors: 
  - name: Person Name
    type: Painting
    description: Abstract work, large and small, in oil and goauche, often drawn from
    email: email@address.com
    telephone: 0112312312312312
    image: images/150x150.png
  - name: Second Person
    type: Painting
    description: Abstract work, large and small, in oil and goauche, often drawn from
    email: email@address.com
    website: https://website.com
    telephone: 0112312312312312
    image: images/150x150.png
---
```

The file must start and end with `---` that's just the way life is I'm afraid

`layout` : stop ("its a stop on the trail")

`title` : the title to display when someone clicks on the map - and the title for the stop in the descriptions

`latitude`, `longitude` : a pain in the arse, get these from dropping a pin onto google maps in the right place

`number` : this must be a UNIQUE, number for the stop, displays the number on the map and in the descriptions

`hours` : free text - this appears under the title of the stop in the description section

`other` : free text - any other info - displayed after the hours in the description section

`icons` : you can pick any icon you can see here : https://materializecss.com/icons.html

    ### be careful to specify 1 icon per line
    ### use a 2 space and a hypen to introduce each line:
    
    ```
    icons:
      - ac_unit
      - account_balance
     ```
     
`exhibitors` : a list of exhibitors - be a bit careful here

    ### each exhibitor is started with a `- name:` everything up to the next `- name:` or the end of the file is about that exhibitor
    
    `  - name` : Their name
    
    `type`: The type of work they do (e.g. Oil Painting)
    
    `description`: a description of them and their work
    
    `email` : Their email address
    
    `telephone` : Their telephone number
    
    `website` : Their website - include the https://
    
    `image` : an image that you've uploaded (into the images folder)


# Project REST-Rant

REST-Rant is an app where users can review restaurants.

#### GET _/_ **Home page*
#### GET _/places_ *Places index page*
#### POST _/places_ *Create new place* 
#### GET _/places/new_ *Form page for creating new place*
#### GET _/places/:ID_ *Details about a particular place*
#### PUT _/places/:id_ *Update a particuliar place*
#### GET _/places/:id/edit_ *Form page for editing an existing pLace*
#### DELETE _/places/:id_ *Delete a particulate place*
#### POST _/places/:id/rant_ *Create a rant (comment) about a particular place*
#### DELETE _/places/:id/rant/:rantld_ *Delete a rant (comment) about a particular place*
#### GET _*_ *404 page (matches any route not defined above)*

## DATA :
- **name** (string)
- **city** (string)
- **state** (string)
- **pic** (string)
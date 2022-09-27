# Coding challenge

### Isten hozott a Hotel Transilvaniában!   
A feladatod az lesz hogy létrehozz 2 oldalt, a csatolt figma file alapján.   
Az első oldalon ami egyben a nyitóoldal a hotel aktuális vendégeit kell megjelenítened.   
A második oldalon pedig új vendégeket kell tudni hozzáadni a hotelhez.   

A feladat megoldásához szükséges endpointok:

    GET https://crudcrud.com/api/31fcb17b05204056970f818a1b7dd437/guests
    POST https://crudcrud.com/api/31fcb17b05204056970f818a1b7dd437/guests
   
   Egyéb használható endpointok:

    GET https://crudcrud.com/api/31fcb17b05204056970f818a1b7dd437/guests/<id>
    PUT https://crudcrud.com/api/31fcb17b05204056970f818a1b7dd437/guests/<id> 
    DELETE https://crudcrud.com/api/31fcb17b05204056970f818a1b7dd437/guests/<id>

A szerver előre tartalmaz 5 hotel vendéget. Kérlek az általuk meghatározott JSON struktúrát használd, ami egyébként:

    {
    	"name": "Jobbos Tibi",
    	"room_number": 105,
    	"start_date": "2022-09-25T00:00:00.000Z",
    	"end_date": "2022-09-29T00:00:00.000Z"
    }

Figma link: https://www.figma.com/file/Ihj7uXejtX0q8jFoa1HcUd/Hotel-Transilvania?node-id=0%3A1

 A feladat megoldását GitHub-ra töltsd fel és ha publikus akkor küld át az url-t ha hanem akkor adj engem hozzá a projecthez kollaborátorként. (@BergkampHUN)

## Design preview
![Opening screen](https://github.com/BergkampHUN/coding-challenge/blob/main/images/Desktop%20-%201.png?raw=true)
![New guest screen](https://github.com/BergkampHUN/coding-challenge/blob/main/images/Desktop%20-%202.png?raw=true)

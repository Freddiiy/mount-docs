# Character
## `/character/{region}/{realm-slug}/{character-name}`
<br/>

Returns information about a specific character

`/character/eu/tarren-mill/chasie` returns:

```js
{
   "assets":[
      {
         "key":"avatar",
         "value":"https://render.worldofwarcraft.com/eu/character/tarren-mill/30/174115358-avatar.jpg",
         "file_data_id":0
      }
   ],
   "region":"eu",
   "id":174115358,
   "name":"Chasie",
   "level":60,
   "gender":{
      "type":"FEMALE",
      "name":"Female"
   },
   "faction":{
      "type":"HORDE",
      "name":"Horde"
   },
   "race":{
      "name":"Orc",
      "id":2
   },
   "realm":{
      "name":"Tarren Mill",
      "id":1306,
      "slug":"tarren-mill"
   }
}
```

## `/character/mounts/{region}/{realm-slug}/{character-name}`
<br/>

Returns all mounts owned by a character

`/character/mount/eu/tarren-mill/chasie` returns:

```js
[
   {
   "mount": {
   "id": 39,
   "name": "Red Mechanostrider"
   },
   "isUseable": false,
   "isFavorite": false
   },
   {
   "mount": {
   "id": 236,
   "name": "Winged Steed of the Ebon Blade"
   },
   "isUseable": false,
   "isFavorite": false
   },
   {
   "mount": {
   "id": 58,
   "name": "Unpainted Mechanostrider"
   },
   "isUseable": false,
   "isFavorite": false
   },
...]
```

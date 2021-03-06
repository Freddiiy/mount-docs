# Mount endpoint

## `/mount`
<br/>

Returns information about all mounts

`/mount` returns:

```json
[
   {
      "itemId":5656,
      "iconDisplay":"https://render.worldofwarcraft.com/us/icons/56/ability_mount_ridinghorse.jpg",
      "id":6,
      "name":"Brown Horse",
      "creatureDisplays":[
         "https://render.worldofwarcraft.com/us/npcs/zoom/creature-display-2404.jpg"
      ],
      "description":"A favorite among Stormwind's guards thanks to its patience and stamina.",
      "is_useable":false,
      "source":{
         "type":"VENDOR",
         "name":"Brown Horse"
      }
   },
   {
      "itemId":0,
      "iconDisplay":"",
      "id":7,
      "name":"Gray Wolf",
      "creatureDisplays":[
         "https://render.worldofwarcraft.com/us/npcs/zoom/creature-display-2320.jpg"
      ],
      "description":"This breed of wolf prefers hunting in the fog, relying on its smoky hide to camouflage it from unsuspecting prey.",
      "is_useable":false,
      "source":{
         "type":"VENDOR",
         "name":"Gray Wolf"
      }
   }
...]
```

## `/mount/{mount-id}`
<br/>

Returns information about a specific mount

`/mount/13` returns:

```json
{
   "itemId":12330,
   "iconDisplay":"https://render.worldofwarcraft.com/us/icons/56/ability_mount_blackdirewolf.jpg",
   "id":13,
   "name":"Red Wolf",
   "creatureDisplays":[
      "https://render.worldofwarcraft.com/us/npcs/zoom/creature-display-2326.jpg"
   ],
   "description":"Almost none remain in the whole of Azeroth; only the most experienced will have seen one.",
   "is_useable":false,
   "source":{
      "type":"VENDOR",
      "name":"Red Wolf"
   }
}
```

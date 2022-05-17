# Realm endpoint

## `/realm`
<br/>

Returns information about all realms

`/realm` returns:

```json
[
   {
      "name":"Lightbringer",
      "id":1388,
      "slug":"lightbringer"
   },
   {
      "name":"Chants éternels",
      "id":1620,
      "slug":"chants-éternels"
   },
   {
      "name":"Bloodscalp",
      "id":522,
      "slug":"bloodscalp"
   },
   {
      "name":"Dethecus",
      "id":81,
      "slug":"dethecus"
   }
]
```

## `/realm/{region}`
<br/>

Returns information about all realms from a specific region

`/realm/eu` returns:

```json
[
   {
      "name":"Das Syndikat",
      "id":614,
      "slug":"das-syndikat"
   },
   {
      "name":"Kael'thas",
      "id":543,
      "slug":"kaelthas"
   },
   {
      "name":"Garona",
      "id":509,
      "slug":"garona"
   },
   {
      "name":"Burning Blade",
      "id":523,
      "slug":"burning-blade"
   }
]
```

<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/WLCM%20TO -IMRAN MEDIA DOWNLOADER-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Neuton&size=25&color=30FF40&background=000000&center=true&vCenter=true&width=360&height=60&lines=Hello+World%2C+I'm+Mr-IMRAN+Here+🤙;𝙸𝚃'𝚜+𝙽𝙾𝚃+𝙰+𝙹𝚄𝚂𝚃+𝙽𝙰𝙼𝙴+𝙱𝚁𝙾+🥱;𝙸𝚃'𝚜+𝙰+𝙱𝚁𝙰𝙽𝙳+🔥;Respect+Mr.IMRAN+🥀;Thanks+My+All+Friend+🤙+🥰)](https://git.io/typing-svg)

## Get Random Video 


## Get 
``` http://localhost:3000/video/anime ```

```Returns a random anime video in JSON format.
Response:
json
Copy code
{
    "data": {
        "title": "Anime Title",
        "imgurLink": "https://imgur.com/example"
    },
    "count": 10,
    "owner": "Mohammad IMRAN",
    "contact": "www.facebook.com/100075122837809"
}

```

## Add /update Anime Video
```http://localhost:3000/album?title=ANIME_TITLE&url=IMGUR_LINK```

```bash
Adds a new anime video or updates an existing one.
Query parameters:
title: Title of the anime.
url: Imgur link of the anime.
```
```Response:
json
Copy code
{
    "success": "Entry added/updated successfully",
    "data": {
        "title": "Anime Title",
        "imgurLink": "https://imgur.com/example"
    }
}```

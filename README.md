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

```bash Adds a new anime video or updates an existing one.
Query parameters:
title: Title of the anime.
url: Imgur link of the anime.```
Response:
json
Copy code
{
    "success": "Entry added/updated successfully",
    "data": {
        "title": "Anime Title",
        "imgurLink": "https://imgur.com/example"
    }
}```

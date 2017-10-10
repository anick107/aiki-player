# aiki-player
The idea of this player is to provide additional information to the aikido exam preparation videos.

[DEMO -- Open the player](https://anick107.github.io/aiki-player/docs/aiki-player.html)

## How to add/modify video and tags?
Currently all information is stored in [clips.json](https://github.com/anick107/aiki-player/blob/master/docs/clips.json). Example file:
```javascript
[  
   {  
      // label of the clip (for the group box)
      "label":"Aikido Kokoro, 6 kyu", 

      // youtube videoid, can be found in the clip uri
      "videoId":"gRlhNA63-Kc",

      // tags format ->> second: tag
      "rels":{ 
         "9": "mae ukemi",
         "23": "ushiro ukemi"
      }
   },
]
```
Note: actual JSON file should not include comments.

Since it's hosted on github, feel free to pull-request your changes. Extention of the clips database (clips.json) is much appreciated.


## Disclaimer

This is a proof-of-concept version which is not even properly tested. There is a huge room for improvement e.g.:
 * smart search functions
 * url friendly navigation
 * comfy clip tagging interface (with autocomplete)
 * fully interactive examination programme
 * platform for the aikido clubs exam sheets
 * and so much more.

Actually, it looks like a nice small project for a hackathon, so if you're an aikidoka and a front-end ninja, I'd love to team up. Just [ping me](mailto:nick.asmolovsky@gmail.com), I'm in Berlin.

[Repo of the player](https://github.com/anick107/aiki-player)

PS: I know, jquery is not cool anymore. If you can do better, just do it ;-) Any help is welcome.
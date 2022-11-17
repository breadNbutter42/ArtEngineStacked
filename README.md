# ArtEngineStacked
Hashlips art engine modified to extend an existing collection while checking against the previous trait combinations.

In src/config.js make sure to change format settings. Other than that usage same as hashlips art engine.
![image](https://user-images.githubusercontent.com/97899677/202340710-37480825-61d8-4ec1-b294-fa3342e7b918.png)

Added a variable for first token id which you can edit if needed (config.js)
const startEditionsFrom = 3250

Main difference from hashlips engine is DNA generation. 
Rebuilt it so we could generate DNA's from the old files.

Right under layerConfigurations in src/config.js there is overrideChads variable. 
![image](https://user-images.githubusercontent.com/97899677/202341293-51057575-f810-4179-9d6c-d4fb30d8f9cc.png)

....

open folder with VSC code
new terminal: cmd terminal
npm install
node index.js

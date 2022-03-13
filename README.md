# Portfolio
Obaid ur rehman  
obaidurrehman164@gmail.com  
+923342900636  
Rawalpindi, Pakistan

### PandaEditor (Software engineering)
_PandaEditor is a unity or unreal style level/scene editor for Panda3d realtime rendering engine, although several editors for Panda3d already existed when I started working on PandaEditor, however most were either created to fullfill requirements on a per project basics or fell short of maintainance.   
PandaEditor is a personal project of mine, it started with my ambition to increase my practical skills in software design and development....the best discription of PandaEditor is on it's official page._


### FastGrid (Technical artist)
_FastGrid is a very fast grid tile system for unity engine, it was created for large open world terrains and landscapes for various purposes such as_

1. _Placing objects_
2. _Implementing level of details (LODs)_
3. _Frustum culling_
4. _AI characters collision avoidance, an AI character can poll for nearest characters on a particual tile (or it's neighbouring tiles) and plan it's route accordingly._

_FastGrid does not loop over all tiles/cells to search for desired tiles instead it generates samples for a particular test, only one sample is generated for one tile, after all samples have been generated, row and column index of a tile in grid is calculated for each sample and exact tile is pulled from a 2d dimensional array, the method of generating samples depends on type of test, following tests are currently implemented_.

1. _Tiles at this position_
2. _Neighbouring tiles_
3. _Tiles in circular radius_
4. _Tiles in camera FOV_
5. _Tiles in 2d rect_

_The following tests show various tests with following specifications_  
_Terrain size : 4km^2_  
_Tile size : 40m^2_  

![Unity_wlONUzTXnF](https://user-images.githubusercontent.com/23467551/158054074-9a4828b5-e57d-4fe2-aa13-9e4ba86fa01f.gif)

 
### Location Tool (Technical artist)
_Is an AI awareness/navigation system available as a unity editor plugin... using LocationTool any GameObject can be converted to a location, after a GameObject is converted to a location it's boundaries and important destinations in that location can be defined, the location can be duplicated and place around the level, The AI characters can than poll for interested locations at runtime for example _**During rain AI characters can search for nearest rain shelters and move there, until it stops raining**.__   
_Example usage of LocationTool would be._



### Gameplay programming

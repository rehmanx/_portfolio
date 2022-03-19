# Portfolio
Obaid ur rehman  
Software engineer, CG environment artist  
obaidurrehman164@gmail.com  
+923342900636 (whatsapp)
ArtStation page https://www.artstation.com/rehman13
Rawalpindi, Pakistan

### PandaEditor
_PandaEditor is a unity or unreal style level/scene editor for Panda3d realtime rendering engine, although several editors for Panda3d already existed when I started working on PandaEditor, however most were either created to fullfill requirements on a per project basics or fell short of maintainance.   
PandaEditor is a personal project of mine, it started with my ambition to increase my practical skills in software design and development....the best discription of PandaEditor is on it's official page._



### FastGrid
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
_Terrain size : 4km square_  
_Tile size : 40m_  

![Unity_wlONUzTXnF](https://user-images.githubusercontent.com/23467551/158054074-9a4828b5-e57d-4fe2-aa13-9e4ba86fa01f.gif)


### McWorldDesigner
_McWorldDesigner is level design and objects scattering editor plugin for unity3d, suited for_

1. _**objects scattering**_
2. _**foliage scattering**_
3. _**creating roads**_
4. _**rivers**_
5. _**bridges etc. for open world terrains.**_

_McWorldDesigner is a layer based painting tool with larger objects occupying top layers, an layer in McWorldDesigner acts similar to photoshop layers with individual scattering rules, paint options and properties._
_A layer can have it's list of paint objects called a **PaintMesh**, each **PaintMesh** can have it's own spawn options, this provides a lot more fine control over placement of individual **PaintMeshes** and more predictable results._



_**Some results achieved with McWorldDesigner**_



### Open world environment production


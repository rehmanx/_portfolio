# Portfolio
Obaid ur rehman  
Software engineer, CG environment artist      
[ArtStation page](https://www.artstation.com/rehman13m)  
obaidurrehman164@gmail.com  
+923342900636 (whatsapp)  
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

![main](https://user-images.githubusercontent.com/23467551/159134327-29a07bc3-2311-464b-92f5-d5d02a2f1633.jpg)

_**Some results achieved with McWorldDesigner**_

![10994433_919588138054383_7146353291723390675_o](https://user-images.githubusercontent.com/23467551/159134389-49a66f71-70c9-4cda-8fe0-d581451b1110.jpg)
![10996776_919588141387716_1557448902022985795_o](https://user-images.githubusercontent.com/23467551/159134396-f63c2691-74d9-4cd3-bbf8-51b2785cc70b.jpg)
![10403792_919588144721049_4277208660362061481_o](https://user-images.githubusercontent.com/23467551/159134400-ee8e1d0d-0d5f-4cf5-a3e0-829d87d71ea9.jpg)
![10497222_919588154721048_6143104140703961053_o](https://user-images.githubusercontent.com/23467551/159134402-6f8d5cb3-060d-4bb1-a257-06720d27e8b4.jpg)
![10984500_919588148054382_5287412091805308389_o](https://user-images.githubusercontent.com/23467551/159134409-0dbbfd5a-ba94-4fbc-ac29-e8183f86caff.jpg)


### Open world environment production


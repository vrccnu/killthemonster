#虚拟现实砍杀怪物游戏 

##游戏步骤  

1.玩家自动前进  
2.怪物迎面向玩家接近  
3.玩家在合适的时机点击屏幕，砍杀怪物  
4.如果没有砍中，怪物接触玩家则玩家倒下（一局结束）  
5.如果砍中，玩家速度会越来越快  
  
##美术资源初步预计  

玩家模型（或者只有手部）  
砍刀模型  
怪物模型（多种，最好有绑骨）  
场景模型（>=3种）  
砍中特效  
**模型不能太大，注意面数**  

##脚本需求预计  

###初步  

SceneControl.cs  控制游戏整体，怪物的出现、攻击成功失败的判断等  
PlayerControl.cs  控制玩家的行为  
AttackColiderControl.cs  执行攻击判断  
FloorControl.cs  控制背景生成在玩家周边  
OniGroupControl.cs  控制怪物的分组，怪物以组为单位进行移动和碰撞检测  
OniControl.cs  控制怪物的行为  
OniEmitterControl.cs  玩家得分时生成怪物  
OniStillBodyControl.cs  玩家得分时新产生的怪物  
CameraControl.cs  摄像机控制  
TitleSceneControl.cs 标题画面控制  

###进阶  

待补充  

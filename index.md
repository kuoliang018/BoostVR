# Blog Post 1

## In this blog post we discuss the following:

### Project Name: BoostVR

### Team Members: Xiuyuan Chen, Kuo Liang

### Short Description

We plan to implement a racing game in VR, using Oculus Rift and Unity 3D and the game works very much like the IOS game [Boost2](https://itunes.apple.com/us/app/boost-2/id333191476?mt=8), by Jonathan Lanis. Here are some screenshots of the game:

![alt text](https://is2-ssl.mzstatic.com/image/thumb/Purple1/v4/d3/02/8f/d3028fd9-0e9b-c60e-557e-64f1da287924/pr_source.jpg/643x0w.jpg  "Screenshot 1")

![alt text](https://lh4.ggpht.com/1w7bc3BbqJwLWz24M7Dn0Fmd7UJLxCCYivGhSNthVazWtMBf_h8U4sQm2Nnua-5jj5qJ=h310-rw "Screenshot 2")

![alt text](https://d3e4aumcqn8cw3.cloudfront.net/api/file/6fTxPSqCRKGHChEqKUFT "Screenshot 3")

![alt text](https://static-s.aa-cdn.net/img/ios/333191476/531dced50a7bc4db8db307e8c21dd51b "Screenshot 4")

New Pictures:
clients: <br>
![alt text](https://github.com/kuoliang018/BoostVR/blob/master/client1.PNG  "Screenshot 1")
![alt text](https://github.com/kuoliang018/BoostVR/blob/master/client2.PNG  "Screenshot 1")
server:
![alt text](https://github.com/kuoliang018/BoostVR/blob/master/server.PNG  "Screenshot 1")
menu:
![alt text](https://github.com/kuoliang018/BoostVR/blob/master/menu.PNG  "Screenshot 1")
In the game, the player always moves forward in the scene and has to avoid colliding with the colored cudes. The player will be warned by an incoming cube by the change of color on the ground. The patterns of the cubes will become more and more complicated, and the speed of the player will grow over time as well, making it harder and harder to avoid the cubes.

### Technical Features

1. System Control and Symbolic Input

 We would first implement System Control by providing the user with menus. The player should be allowed to set the color theme, starting speed, difficulties, and sound volumns.

2. Navigation and Travel

 The player will automatically proceed in the racing, but they can control to steer left or steer right to avoid collision. Additionally, when there is an obstacle/cube ahead, we will color to whole racing trail to indicate the incoming cube.

3. Multi-Player Mode

 After selecting the multiplayer mode, two players will be put in the same game scene and try to survive as long as possible. In a multiplayer mode, two players can see each other in the tunnel/racing trails and can pick up special items to increase another players' life. This way they have to help each other out in order to get maximum score.

4. Spatial Audio

 A game has no soul without sound effects.

5. Interactive Tutorial

 We will provide traning mode to demonstrate the rules of the game.

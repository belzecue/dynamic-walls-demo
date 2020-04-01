## Dynamic Walls - demo implementation
 
![Alt Text](https://media.giphy.com/media/IhrybqUpXDkMTgRgO6/giphy.gif)

## In-game example
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/uC5QpEmV8FY/0.jpg)](https://www.youtube.com/watch?v=uC5QpEmV8FY)

# About this repository
This demo project showcases dynamic walls whose sides adapt to the environment used in our upcoming game: 
[Pelagos: Rise of Greece](https://www.reddit.com/r/Pelagos/).

It contains a working example scene and commented source code.
This project also uses techniques of Object Pooling and custom Frustum Culling, which can be viewed here: (https://github.com/keypax/object-pooling-in-unity-demo)

## Requirements

Unity 2019.3.2: go to [Unity download archive](https://unity3d.com/get-unity/download/archive) page and download **Unity 2019.3.2** version.
## Installation

Just download ZIP of this repo or use GIT client and open in Unity. That's all :)
## Implementation

This is a demonstration of a solution that we're using in our project. **This is not** an out of the box plugin that you can download and make work in 2 minutes.
In this example we're using **Dependency Injection**. We also try to use Unity components only if necessary.

It may be scary, but don't worry and take a look :)

## Where to start
Good places to start understanding the code are:

`Buildings.Application.WallConfigurator`

`Buildings.Application.WallSidesUpdater`

`Buildings.Application.Spawners.WallSpawner`



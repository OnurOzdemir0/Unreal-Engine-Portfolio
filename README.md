# Unreal Engine Portfolio

_Hi, my name is Onur. Following is a series of different ideas I found inspiring enough to execute in Unreal Engine, and they all showcase a bit of my capabilities in various areas. Thank you for taking the time to visit my portfolio, and I hope you enjoy browsing through my projects._

| Number | Project Name | Inpiration |
| --- | --- | --- |
| 1 | Wrist Grapple | Mandalorian |
| 2 | FOV Boost | Atomic Heart |
| 3 | Double Dash | Celeste |

## Projects
### 1. Wrist Grapple

In the series [Mandalorian](https://www.imdb.com/title/tt8111088/), the character uses a wrist grapple to both pull objects to himself and pull himself to the objects. I find the concept of using the same button to perform two different actions to be an interesting engineering topic.

![Mandalorian](https://lumiere-a.akamaihd.net/v1/images/grapple-line-main_92f159e7.jpeg?region=131%2C0%2C951%2C536)

To create this effect, I used the cable component of Unreal Engine 5.1. Cable length changes according to the distance of target. If there is no target within the reach of our cable, nothing happens. It is physics based, so there is a slight gravity acting on the hook. Right now, it checks whether if the target simulates physics. Which is scalable, as it can be improved for various targets. I modeled the metal "hook" part using Blender.  

You can watch a better quality Youtube video [here](https://www.youtube.com/watch?v=fdR5riQKFnU).
(backup link: https://www.youtube.com/watch?v=fdR5riQKFnU)

Here is also a low quality GIF of my implementation.

![Grapple](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYWY3YzM2MTkwYmI4NWZlOTZmYmQyNmM2NDQ0YjgxYjk2MzcyNmJjNyZjdD1n/WaA7A54pvSydFtN2J7/giphy.gif)

### 2. FOV Boost
In Atomic Heart as character moves forward, there is a slight boost on FOV (Field of View), which enhances the immersion.


![Atomic Heart (2023)](https://media.giphy.com/media/YZYXX07HvwTBde7wcU/giphy-downsized.gif)


Atomic Heart inspired me to immitate this effect on Unreal Engine 5. Weight of the effect is easily adjustable.

![Atomic Heart (2023)](https://media.giphy.com/media/TiW2tX1IMQXR1uLIOX/giphy.gif)

This effect can be used in vehicles. (spaceships, fast cars, jetski etc.)

# Bird Hunt

**Bird Hunt Game** written in `C++`, using `GLFW` and `GLM` libraries,
which are contained in the [GFX Framework](https://github.com/UPB-Graphics/gfx-framework).

The game's idea is to kill as many birds as possible,
in order to achieve a high level without dying.

![In-Game Picture](/samples/birdhunt1.png "First level view")

## How to play

Just open the `.exe` file in the `\bin\Debug` folder and make sure
you have all the necessary DLLs installed. It it doesn't work, build the
project with `CMake` and compile it manually.

## Gameplay Flow

Initially, the player has only **3 lives**. Each escaped bird means one life gone.\
For each bird, the player is given **3 bullets**.
If the bullets are gone without killing the bird,
or it is not caught in a proper time, it escapes.

Each level consists of **6 birds** to be killed.

If all lives are gone, the game is over.

## Bonuses

- Level 5 - one bonus life
- Level 6 - one bonus life + one bonus bullet from now on
- Level 7 - The **King Bird**, which has 3 lives (so it has to be shot 3 times).
If this bird escapes, it is game over.

![King Bird Picture](/samples/birdhunt2.png "King Bird level image")

- Level 8 - From now on, the **Slow Motion** Feature is available.
The player is initially given 5 seconds of power-up. Each new level,
2 more seconds are added to the **Slow Motion Charge Bar**.\
This feature can be enabled and disabled by pressing the `Left Shift` key.

![Slow Motion Picture](/samples/birdhunt3.png "8+ level overview")

## License

[Adrian-Valeriu Croitoru](https://github.com/adriancroitoru97)
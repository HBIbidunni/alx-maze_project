# The ALX Project - The Maze Game
--------------

The __Maze Game Project__ is about creating a 3D game using raycasting techniques. 
Raycasting is a rendering technique used in computer graphics to simulate 
a `3D environment` in a `2D space`. The project is to be implemented on `Ubuntu 14.04 LTS` 
using the GCC compiler and the SDL2 and SDL2_image library for graphics and input.

After the installation of SDL2, the test below was carried out to verify that SDL2 has been correctly installed on `Ubuntu 14.04 LTS`

``` 
#include <SDL2/SDL.h>

int main(int argc, char* argv[]) {
    if (SDL_Init(SDL_INIT_VIDEO) != 0) {
        printf("SDL initialization failed: %s\n", SDL_GetError());
        return 1;
    }

    SDL_Window* window = SDL_CreateWindow("SDL2 Test", SDL_WINDOWPOS_CENTERED, SDL_WINDOWPOS_CENTERED, 800, 600, 0);
    if (!window) {
        printf("Window creation failed: %s\n", SDL_GetError());
        return 1;
    }

    SDL_Delay(3000);

    SDL_DestroyWindow(window);
    SDL_Quit();

    return 0;
}

```

More vital updates to be added into the project and README.md.

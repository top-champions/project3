#include <SDL2/SDL.h>
#include <SDL2/SDL_image.h>
#include <iostream>
#include <cstdlib>
#include <ctime>
#include <math.h>
using namespace std;
#define PI 3.14159265
const int SCREEN_WIDTH = 600;
const int SCREEN_HEIGHT = 900;

struct balls
class balls1
{
    public:
    int x;
    int y;
    int a;
    int v;
    int m;
    void intialize()
    {
        

    }
    move()
    {
         
    }
    void showline()
    {
        SDL_RenderDrawLine(renderer, , 50, SCREEN_WIDTH, 50);
    }
}
void init(int* v)
{

}
int main()
{
     SDL_Init(SDL_INIT_VIDEO);
    window = SDL_CreateWindow("Mojtaba", SDL_WINDOWPOS_UNDEFINED, SDL_WINDOWPOS_UNDEFINED, SCREEN_WIDTH, SCREEN_HEIGHT, SDL_WINDOW_SHOWN);
    SDL_Renderer *renderer = SDL_CreateRenderer(window, -1, SDL_RENDERER_ACCELERATED);
    balls1 a[5];
        while(true)
        {
            SDL_SetRenderDrawColor(renderer, 0, 0, 0, SDL_ALPHA_OPAQUE);   
            filledCircleRGBA(renderer, a[i].x, a[i].y, a[i].dia, 255, 255, 255, 255);   
        }
    return 0;
}


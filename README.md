# The Maze

![Repo size](https://img.shields.io/github/repo-size/AsuweRich/The-Maze-Project)
![Repo License](https://img.shields.io/github/license/AsuweRich/The-Maze-Project.svg)
![Latest commit](https://img.shields.io/github/last-commit/AsuweRich/The-Maze-Project/main?style=round-square)

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in `C` ussing `SDL2` library. Deveploment was performed using `Ubuntu 14.04 LTS` - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

### About SDL2 

`Simple DirectMedia Layer` is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via `OpenGL` and `Direct3D`. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
$ git clone https://github.com/AsuweRich/The-Maze-Project.git
```
## Usage 
* Use up and down arrow keys to move forward and backward (keys `w` and `s` serve the same function)
* Use right and left arrow keys to turn the camera arround (keys `d` and `a` serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze sdl2-config --cflags sdl2-config --libs;
```
## Running
After successfully compiling run the program using following command:

```bash
./maze MAP
```
where ```MAP``` is the name of the file found in the maps folder. You can create other maps and pass them while running program as above. Map files accept only the allowed characters.

## Flowchart
![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)

## Directories

[`src`](https://github.com/AsuweRich/The-Maze-Project/tree/main/src)

Contains all the source code files written in C.

[`inc`](https://github.com/AsuweRich/The-Maze-Project/tree/main/inc)

Contains all the header files.

[`maps`](https://github.com/AsuweRich/The-Maze-Project/tree/main/maps)

Contains map data files. This will be used by the program to output the map layout.

[`images`](https://github.com/AsuweRich/The-Maze-Project/tree/main/images)

Contains image files.

## Images

![image](https://user-images.githubusercontent.com/44834632/138765500-bd3838d0-fe46-4018-87b0-21143fb77e8b.png)

 
## Texture sources

**Weapon**

https://www.seekpng.com/idown/u2w7u2t4i1y3a9y3_call-of-duty-guns-firearms-gun-weapons-coat/

## Contributing

- Read the source files in ```src``` folder and the header files in ```inc``` folder.
- Clone the repo and make a new branch: `$ git checkout https://github.com/AsuweRich/The-Maze-Project -b [name_of_new_branch].`
- Add a feature, fix a bug, or refactor some code :)
- Write/update tests for the changes you made, if necessary.
- Update README.md if necessary.
- Open a Pull Request with a comprehensive description of changes.

## Demo
[![The Maze Demo](https://i.imgur.com/5Ss7s1S.png)](https://www.youtube.com/embed/6T2N8gNUTQ8)

## Author
Nene Eye [@neneeye](https://github.com/neneeye) <neneeye@gmail.com>

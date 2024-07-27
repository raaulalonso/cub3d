# cub3d

 [![Intro](https://img.shields.io/badge/Cursus-Cub3d-success?style=for-the-badge&logo=42)](https://github.com/raaulalonso/cub3d)
 
 [![Stars](https://img.shields.io/github/stars/raaulalonso/cub3d?color=ffff00&label=Stars&logo=Stars&style=?style=flat)](https://github.com/raaulalonso/cub3d)
 [![Size](https://img.shields.io/github/repo-size/raaulalonso/cub3d?color=blue&label=Size&logo=Size&style=?style=flat)](https://github.com/raaulalonso/cub3d)
 [![Activity](https://img.shields.io/github/last-commit/raaulalonso/cub3d?color=red&label=Last%20Commit&style=flat)](https://github.com/raaulalonso/cub3d)

This project is inspired by the classic Wolfenstein 3D game. It involves creating a dynamic 3D graphical representation of a maze using ray-casting techniques. Developed in C with miniLibX, the project focuses on core programming skills, graphical algorithms, and efficient memory management.

### Features:
- First-person perspective maze exploration
- Smooth window management
- Wall texture variation based on orientation
- Configurable floor and ceiling colors
- Basic player movement and view control
- Wall collisions
- Minimap system

## Preview
https://github.com/user-attachments/assets/5bb36ff5-6551-4443-92a5-fda23db69242

## Installing and running the project:

> ℹ️ This project is done using [Codam MLX library](https://github.com/codam-coding-college/MLX42). If something MLX related is not working on your computer, make sure to check their documentation.

1- Clone this repository
	
	git clone https://github.com/raaulalonso/cub3d.git
2- Navigate to the new directory and run `make`
	
	cd cub3d
   	make
3- Execute cub3D binary with a map of your choice, for example:

	./cub3D maps/valid/map6.cub

## Compiling the Program
The cub3D program comes with a Makefile that includes the following rules:

- `all`: compiles the program.
- `re`: recompiles the program.
- `clean`: removes obj directory with objects files.
- `fclean`: removes obj directory with objects files and cub3D binary.
- `test`: executes a script to check parsing status of all maps in `maps/invalid` folder.

## Disclaimer
> At [42School](https://en.wikipedia.org/wiki/42_(school)), almost every project must be written in accordance to the [Norm](https://github.com/MGuardia10/42cursus/blob/main/subjects/en/norm_en.pdf), the school's coding standard. As a result, the implementation of certain parts may appear strange and for sure had room for improvement.

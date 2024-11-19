

## Updated

1. Added the key events for the speed and angular speed. (Jul. 2024)
2. Fix the code to host my custom splat results URL. Instead of using chunked rendering, whole PLY file is now downloaded from the host(huggingface) and used to render the scene. (Jul. 2024)


## Links for my custom splatted scenes

1. [https://nerfs-eye-view.github.io/3dgs-viewer/?url=konkuk_library.ply](https://nerfs-eye-view.github.io/3dgs-viewer/?url=konkuk_library.ply)
2. [https://nerfs-eye-view.github.io/3dgs-viewer/?url=church.ply](https://nerfs-eye-view.github.io/3dgs-viewer/?url=church.ply)


## controls

movement (arrow keys)

- left/right arrow keys to strafe side to side
- up/down arrow keys to move forward/back
- `space` to jump

camera angle (wasd)

- `a`/`d` to turn camera left/right
- `w`/`s` to tilt camera up/down
- `q`/`e` to roll camera counterclockwise/clockwise
- `i`/`k` and `j`/`l` to orbit

camera velocity (Added)

- `[`/`]`: decrease/increase the speed of camera movements
- `;`/`'`: decrease/increase the angular speed of camera rotations

FOV control (Added)

- shift + `[`/`]`: decrease/increase the FOV

trackpad
- scroll up/down to orbit down
- scroll left/right to orbit left/right
- pinch to move forward/back
- ctrl key + scroll up/down to move forward/back
- shift + scroll up/down to move up/down
- shift + scroll left/right to strafe side to side

mouse
- click and drag to orbit
- right click (or ctrl/cmd key) and drag up/down to move forward/back
- right click (or ctrl/cmd key) and drag left/right to strafe side to side

touch (mobile)
- one finger to orbit
- two finger pinch to move forward/back
- two finger rotate to rotate camera clockwise/counterclockwise
- two finger pan to move side-to-side and up-down

other
- press 0-9 to switch to one of the pre-loaded camera views
- press '-' or '+'key to cycle loaded cameras
- press `p` to resume default animation
- drag and drop .ply file to convert to .splat
- drag and drop cameras.json to load cameras

## other features

- press `v` to save the current view coordinates to the url
- open custom `.splat` files by adding a `url` param to a CORS-enabled URL
- drag and drop a `.ply` file which has been processed with the 3d gaussian splatting software onto the page and it will automatically convert the file to the `.splat` format


## Acknowledgments
This project is based on the work from [antimatter15/splat](https://github.com/antimatter15/splat).

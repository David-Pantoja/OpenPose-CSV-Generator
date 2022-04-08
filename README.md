# 👋 OpenPose-CSV-Generator
Author: UltraPotato2 🥔

This script was written to crawl through each suitable video file in a folder, no matter how deep it was, run it using openpose, extract the 25 important joints' x&y coordinates, combine them with the rest of the file's coordinates, and produce a CSV. This process does open the video window, making your PC effectively unusable during generation time as the cursor refocus each time a new video is played.

## Things to note:
- This was only tested on Ubuntu and assumes openpose is functional on your system.
- To stop the software, go to **Kernal** and press **Restart** or some similar variation of it, depending on what you want to accomplish. After that, click on the openpose windows that keep popping up and press **Esc**.
- Remember to carefully read annotations in the jupyternotebook. They include things like where folder destinations should point to.

# Video To Camera Synchronisation Test Patterns

This is a set of simple video test patterns for testing the synchronisation of a video display to a camera. This is a common workflow for Virtual Production and broadcast. 

# The Methodology

The file contains two basic tests for testing synchronisation. A strobe test and a moving lines test. The video clip should be played back from a media server of your choice within a genlocked enviroment. You should record the video clip been presented on the video wall with your camera. Playback the videoclip to review whether the syncrhonisation is good or bad. 

If you are using multiple LED processors to drive the wall ideally you would test all seams to ensure continuity. However this test is primarily for camera to video testing.

## Strobe Tests

The video features two strobe tests, first a black and white, second a cyan and magenta. These present sequentially in and on off fashoion. 

To validate synchronisation playback the clip. If you are seeing whole frames of black, white, cyan, and magenta your sync is good. If you are seeing any bleeding of colours or gradients your sync is bad. 

### Good Strobe Frame Examples
Below are two good examples of clean frames. There is artefacting from the lens and the moiré but we are just looking at the colour consistency. 

![BlackFrameClean](https://github.com/user-attachments/assets/e742261c-ad89-47db-975d-e599a69d8ed5)

![MagentaFrameClean](https://github.com/user-attachments/assets/83662627-e2f4-4f8f-9c7d-1e74a0cfa385)

### Bad Strobe Frame Examples
1.1 A black and white frame blending to create grey.

![BadBlackWhite](https://github.com/user-attachments/assets/c64c5f7a-ec9a-4a88-ac99-625c066a861b)

1.2 Cyan & Magenta blending.

![BadCyanMagenta](https://github.com/user-attachments/assets/05c3230d-9d90-4a51-8722-83b45cfb6763)

1.3 Black and white frame in closer sync but some artefacting visible at top of frame. 

![BadBlackWhiteCloser](https://github.com/user-attachments/assets/63f2a740-1df2-45f6-843f-4838f562348e)

## Line Tests
The line test is useful as it can present itself more obviously to the human eye on the camera monitor or viewfinder. The tests present a single moving horizontally moving line, then multiple lines, then repeats vertically. 

### Good Line Frame Examples
In the below you can see the lines presenting as one solid line with no tearing or ghosting. 

![GoodLineTestHorizontal](https://github.com/user-attachments/assets/72767b8a-9703-41c9-a027-8e10e017bbdc)

![GoodLineTestVertical](https://github.com/user-attachments/assets/f9d63a85-17e9-458c-a552-5521f5893634)

### Bad Line Frame Examples

2.1 Example of a single line test ghosting

![BadLineTest](https://github.com/user-attachments/assets/8efaa213-f0a5-48d6-b6e7-bd74dfb8ff55)

2.2 Example of a multiple line test ghosting

![BadLineTest2](https://github.com/user-attachments/assets/cce34a9f-f5ae-4a5c-a057-5d61644f3f80)

2.3 Example of a vertical line test ghosting

![BadLineTest3](https://github.com/user-attachments/assets/f530c1e6-bd0a-45e9-80b0-b71753342bf7)

## Adjust Sync
Use the tools on you camera or on your genlock geneator to offset the camera from the video system or vice versa. Record the test again and review results. Repeat until clean frames are presented. 

# License

The test patterns on this page are created by David Gray trading as Virtual Pixels. 

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

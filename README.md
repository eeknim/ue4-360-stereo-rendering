# ue-sandbox 
- to render 360 stereoshot
- modified a built-in plugin stereo panoramic movie capture

- To encode screenshots to movie use follwing commandline using [ffmpeg](https://ffmpeg.org/) :

"ffmpeg.exe -framerate 60 -i D:/CaptureFrames/2017.07.03-21.02.34/Frame_%%5d.jpg -c:v libx264 -profile:v high -level 4.2 -r 60 -pix_fmt yuv420p -crf 18 -preset slower MyMovie.mp4"

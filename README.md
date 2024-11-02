Supported specifications:

1. File format: `.wav`
1. Number of Channels: `Mono` or `Stereo`
    
    > Note: In sterio, only the first channel is used

1. Sample rate: `<= 16kHz`
1. Bitrate: `<= 256 kbps`
1. Duration: `<= 10 sec`

Note that these are not strict limits, rather they are recommended specifications based on memory usage of the application.

If you have an audio file of some other properties, use ffmpeg (or any similar tool) to convert it to the recommended format.
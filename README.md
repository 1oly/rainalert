rainalert
=========
Development of a rainfall warning system.

The outline:

1. Use [wradlib](http://wradlib.bitbucket.org) to read and clean radar data.
2. Use [OpenCV](http://opencv.org) to calculate optical flow
3. Extrapolate from velocity data and use [Thesis about nowcasting](http://dspace.mit.edu/bitstream/handle/1721.1/17006/54449681.pdf?sequence=1) to predict precipitation. Also, check out [How DarkSky works](http://blog.jackadam.net/2011/how-dark-sky-works/) to get inspired.
4. Collect it all on a Raspberry Pi and set up a webserver such that alerts can be accessed from a smartphone.
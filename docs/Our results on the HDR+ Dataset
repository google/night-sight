# Supplement: Our results on the HDR+ Dataset

The following Photos albums show a comparison between [[Hasinoff et al., 2016]](https://hdrplusdata.org/)*  and our algorithm on the [HDR+ dataset](https://hdrplusdata.org/dataset.html).

* [Comparison between HDR+ and our results](https://photos.app.goo.gl/Mzpjka64mUGYhNN89)
* [Our results](https://photos.app.goo.gl/M8A4hkvEgTRd6Gs46)

Note that these results diverge from the system described in our paper in two important ways:
The HDR+ dataset was not captured using motion metering, and the exposure times used are generally shorter than what our system would have chosen. This leads to noisier than usual results for our system. Also note that we haven’t re-tuned our processing to compensate for this extra noise.
To produce optimal results, the auto white balance algorithm needs calibration. However, the devices in the HDR+ dataset have not been explicitly tuned for white balance, and they are missing per-unit white balance calibration data entirely.
Consequently, the results of our system on the HDR+ dataset should not be taken as representative of the image quality of [Night Sight on Pixel phones](https://ai.googleblog.com/2018/11/night-sight-seeing-in-dark-on-pixel.html).

Our system, as described in “Handheld mobile photography in very low light”:
![our_system](./Our_system.png)

Using our system to post-process the HDR+ dataset:
![hdr_system](./HDR+_system.png)

### Additional notes:
- Most of the HDR+ dataset is not captured in low light. Our system produces very similar results in these cases; the main difference is the color rendition, due to the new white balance algorithm.
- Even though the input frames for both methods are the same, our system merges more frames compared to HDR+. On average it merges one frame more than HDR+ (7.6 frames compared to 6.7 frames, respectively).
- Our paper presents the general algorithm for Night Sight as it was released in November 2018. However, Night Sight has been continuously improved with software updates for Pixel phones, including support for [astrophotography](https://ai.googleblog.com/2019/11/astrophotography-with-night-sight-on.html).
- An earlier version of these results (shared between Oct 29, 2019 and Jan 7, 2020) was compromised by a configuration error that affected older bursts. Please use the most recent results only.


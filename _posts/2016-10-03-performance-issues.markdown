---
layout: post
title:  "Performance"
date:   2014-10-03 15:00:00
excerpt: |+
    - \* Why quality factor and piezoelectric coupling coefficient important?
    - \* How is your device performance compared to the device fabricated on silicon ?
    - \* Chen et al reported FBAR device directly fabricated on PI with quality factor as high as 970, so what's your advantage over them?
---
### Why quality factor and piezoelectric coupling coefficient important?

For applications in wireless communication such as radio frequency filter. High quality factor means more idealized shape of filter transmission curve and lower power consumption. The piezoelectric coupling coefficient directly influenced the bandwidth of the filter. Small or large coupling coefficient is needed for different purpose, however the maxim coupling coefficient a device can achieve is limited by the intrinsic properties of piezoelectric material. As to aluminum nitride, this value is around 0.06.

For applications as mass sensor, high quality factor means better signal to noise ratio and lower power consumption of the sensor.

For applications as acoustic actuator, high coupling coefficient is needed in order to achieve a higher electrical-mechanical energy conversion efficiency.

### How is your device performance compared to the device fabricated on silicon ?

Following cited from [1], page 126, which briefly reviewed the quality factor footprint of the silicon based FBAR device fabricated in industry lab.

<div class="table-wrapper" markdown="block">

|  Year  | 1993 | 1995 | 2000 | 2002 | 2006 | 2007 |
|--------|------|------|------|------|------|------|
|Q factor| small| ~500 |~1000 | ~2000| ~3000| ~3200|

</div>

It can be seen that our device nearly catch up with the performance of silicon FBAR at year 2000. However, this quality factor can be further enhanced by adjusting the cavity size and the alignment of the device with the cavity. By using transfer print method, our device had great potential in achieving the performance which state-of-art FBAR can achieved on silicon, but the performance sometimes may compromise with device stability, especially on flexible substrate, so several trade-offs must be made.

### Chen et al [2] reported FBAR device directly fabricated on PI with quality factor as high as 970, so what's your advantage over them?

We are using recommended method in Chen's work [3] while calculating quality factor. A more simplified method was using the 3dB width method:

$$
Q = f/\Delta f
$$

where $$\Delta f$$ is the 3dB width of the resonant peak in **frequency impedance curve**. However, in Chen's paper, neither impedance curve nor smith chart were showed. It seems that they are using 3db width of the scatter parameter curve while calculating the quality factor, which may yield a very confusing result. Piezoelectric coupling coefficient, as another important performance factor for FBAR, was not mentioned in their work too.

Well compatibility with variety of substrate and fabrication process is another advantage of transfer print technique over direct-fabricate method.



[1] Hashimoto, Ken-ya. *RF bulk acoustic wave filters for communications.* Artech House, 2009.

[2] Feld, David A., et al. "After 60 years: A new formula for computing quality factor is warranted." 2008 IEEE Ultrasonics Symposium. IEEE, 2008.

[3] Chen, Guohao, et al. "Film bulk acoustic resonators integrated on arbitrary substrates using a polymer support layer." Scientific reports 5 (2015).

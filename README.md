# Fixing Dr.Rhythm DR-550 MKII 

**WARNING!** This is the documentation of how **I** fixed **my** DR-550 MKII. It is **not** a tutorial. **Trying to fix your machine this way may lead to irreparable damage. It definetly would modify it irreversible. Please note that all modification of your device is on your own risk and responsibility.** 

I got one of those defective DR-550 MKII with extremely low and noisy signal on the outputs. And I couldn't find any documentation on how to fix it. But it was a huge help to find the "service notes" manual online, including the circuit diagram of the entire machine here: https://www.synthxl.com/boss-dr-550-mkii/ (PDF: https://www.synthxl.com/wp-content/uploads/2020/03/Boss-DR-550-MKII-Service-Notes.pdf)

I could hear the signal very low on the left headphone which gave me hope that the entire digital part of the machine would be ok and that just the analog output amplifiers would be the problem. I was not able to find any visual indications of faulty components. Capacitors and everything else looked good. So the next idea was to find the output pins of the digital-analog converter (DAC) to see if there was actually a proper analog signal produced.

With the help of the service manual I was able to identify IC103 as the DAC chip and PINs 6 and 11 to be the primary analog output pins.



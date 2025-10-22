# Challenge — Location (100)

## Description  
Find out from where the photo was taken.  

**Author:** Bl4ckf1sh  
**Flag Format:** `CYBERCON_2025{XX.XXXXXX,XX.XXXXXX}`  

---

## Solution  
The challenge provided a **photo of a bridge** with no other clues.  

I started by running a **reverse image search on Google Images**, which identified the place as:  

#### `The Daxi Bridge, Daxi District, Taoyuan City, Taiwan`

Next, I opened the location on **Google Maps** to confirm the surroundings.  
However, the picture appeared to be taken **from an elevated angle**, which made it tricky to pinpoint the **exact coordinates**.  

The **Street View 360°** feature didn’t help much either—it often jumped to the wrong angle or nearby streets.  
So I switched to manual map exploration and began guessing vantage points directly from the terrain and bridge orientation.  

After a few tries, I finally found a **matching view** here:  
 [Google Maps Link](https://www.google.com/maps/@24.885723,121.287014,3a,75.3y,266.61h,79.87t/data=!3m11!1e1!3m9!1sCIHM0ogKEICAgID4xInxLQ!2e10!3e11!6shttps:%2F%2Flh3.googleusercontent.com%2Fgpms-cs-s%2FAB8u6HZH-kUb5jZ_FvAPITSGfXvpaQDGcUaNKkh7edAbpx2Gq4tnwF1aWp5gB17WbKaYBrayVVF7MNNx4SE_fUaSsF5bXQsQNt-RP1_3CTicL-mJ1bNivWV8hv_kPNiotEtpdGGFKIU%3Dw900-h600-k-no-pi10.126610639919974-ya46.61378027072317-ro0-fo100!7i10240!8i5120!9m2!1b1!2i27!5m1!1e1?entry=ttu)  

The coordinates extracted from the URL were:  
## `24.885723,121.287014`


---

## Flag  
**`CYBERCON_2025{24.885723,121.287014}`**

---

## ⚠️ Note  
The given flag format in the challenge description was **slightly misleading**,  
which caused confusion for many participants (including me) before realizing the coordinate format had to be exact.  


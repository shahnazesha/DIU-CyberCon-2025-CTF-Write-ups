# Challenge
## Fragmented Secrets (50)
**Description:**  
A mysterious video contains fragments of a secret. Decode them all before they vanish — only then will the hidden truth be revealed.  

**Author:** Bl4ckf1sh  
**Flag Format:** CYBERCON_2025{s0M3th1ng_H3R3}

---

## Solution
The provided video contained **43 QR codes** flashing quickly over ~20 seconds.  
I took screenshots of each frame containing a QR code and decoded them individually.

After decoding, I combined the fragments into a single string:

### Q1lCRVJDT05fMjAyNXs1M2NyMzc1XzFuX3FyX2MwZDN9


Then decoded it from **Base64**, revealing the final flag.

---

##  Flag
**CYBERCON_2025{53cr375_1n_qr_c0d3}**



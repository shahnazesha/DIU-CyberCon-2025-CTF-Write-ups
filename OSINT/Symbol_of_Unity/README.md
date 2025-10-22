# Challenge

**Name:** Symbol of Unity 100  
**Author:** Bl4ckf1sh  
**Flag Format:** `CYBERCON_2025{openingtime_closingtime}`  

---

## Description

The library is considered a symbol of unity because of its uniqueness. Three months ago, one of my friends visited the library and had a very good time. However, from the Library Hours, he found that on that day the library was open for tours only. The task was to find the opening and closing time of that day.

An image of a library was in attachment.

---

## Steps I Followed

My first instinct was to perform a Google image search on the provided picture, but it didn’t return any known library. I also tried Aperisolve to analyze the image’s metadata and see inside it for hidden clues, but that too led nowhere. At this point, it became clear that the image itself wasn’t going to give the answer.

Next, I focused on the text description and the keywords it contained: "symbol of unity," "library," and "unique." I used these keywords to search on Google with queries like `"symbol of unity" library`, `"library considered a symbol of unity"`, and `"unique library connecting countries"`. These searches pointed me first to the United Nations and then to the Haskell Free Library, which is known as a library connecting countries and considered unique.

Since the challenge mentioned that the event happened three months ago, and the file metadata showed a creation date of October 1, 2025, the relevant timeframe was June 2025. I then checked whether either the UN Library or the Haskell Free Library had any "tours only" days in June. The UN Library’s public access is limited and only allows guided tours during meetings, so there was no match.  

Finally, I found an Instagram post from the Haskell Free Library announcing that starting Sunday, June 29th, they would be open from 12:00 to 4:00 **for tours only**, which perfectly matched the challenge clue.

---

## Tools

- **Aperisolve**: [aperisolve](https://aperisolve.com)
- **EXIF Analysis Tool**: [exif.tools](https://exif.tools)   

---

## Conclusion

By combining keyword-based Google searches, careful attention to the timeframe, and verifying library announcements, I determined that the library was open for tours only on June 29, 2025, from 12:00 to 4:00.  

The flag is:

### `CYBERCON_2025{12:00_4:00}`

---

## References

Haskell Free Library Instagram Post: [instagram](https://www.instagram.com/p/DK2ED69vqFz/)

## ⚠️Note 

The flag format was somewhat ambiguous. It was unclear whether times should be in **12-hour or 24-hour format**, whether to include **AM/PM**, or whether to use **":"** or another separator like **"--"**. Careful attention to the challenge examples is recommended when submitting.

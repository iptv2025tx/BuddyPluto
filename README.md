# 🍻 Cheers n Thank You 🍻
This script was created by BuddyChewChew, who has been working on scripts for a while. 

# 📺 Pluto TV Custom Playlists
Automatically updated M3U playlists for Pluto TV with forced HD resolution and country-based grouping.

## ✨ Key Features

* **Forced HD Resolution:** Script mimics a Chrome 133 Desktop client on `x86_64` to force Pluto to serve **720p/1080p** manifests.
* **Stable Commercials:** Uses optimized regional IP headers (`X-Forwarded-For`) to prevent freezing or pausing during ad transitions.
* **Country-Based Grouping:** The **All Regions** playlist ignores standard categories and groups channels strictly by their country.
* **Auto-Update:** Playlists are refreshed every 6 hours via GitHub Actions to ensure streams remain active.

---

## 🛠️ How to Use

1.  **Copy** one of the M3U links from the table above.
2.  **Paste** it into your IPTV player (TiviMate, OTT Navigator, VLC, etc.).
3.  Add the **EPG URL** to the TV Guide section of your app.
4.  **Note:** If you were using the old `pluto_master.m3u` or `pluto_uk.m3u`, please switch to `pluto_all.m3u` and `pluto_gb.m3u` respectively.

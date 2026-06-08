# tori-tore_adaptive
The source codes of TORI-TORE are placed on this page. Quiz training allows adaptive training and baseline training as described in the paper (Ogawa et al. 2023).
Please refer to the paper for the adaptive training and baseline training algorithms.
Ogawa Y, Fukasawa K, Yoshioka A, Kumada N, Takenaka A, Ito T. 2023. Quiz-style online training tool helps to learn birdsong identification and support citizen science. PeerJ 11:e15387 https://doi.org/10.7717/peerj.15387

## How to use
This repository contains the application logic and source codes. To run the system, please follow these steps:

1. **Deploy to Web Server**: 
   Place the source files into the document root (e.g., `htdocs`) of your web server software, such as Apache HTTP Server.

2. **Add Media Assets**: 
   **IMPORTANT: Audio (`mp3/`) and image (`img/`) files are NOT included in this repository due to copyright restrictions.** To make the quiz functional, you must provide your own media files and place them into the respective `mp3/` and `img/` directories.

3. **CGI and Permissions**: 
   Ensure that your server is configured to execute CGI scripts (Perl). Proper write permissions must be granted to the `data/` directory for saving quiz results.

---
## [IMPORTANT NOTICE]
This license applies primarily to the source code within this repository. 
Regarding media assets (audio, spectrograms, and images), the terms vary depending on the author and source:

* **Sample Assets Included in This Repository (CC BY 4.0):** We have included a set of sample bird images provided by **A. Takenaka**. These specific assets are explicitly included under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. You are free to share and adapt them, provided that proper credit is given to the author (A. Takenaka).
* **Excluded / Private Assets:** Audio files (`mp3/`) and certain other images used in the live version of this project are **EXCLUDED** from the default repository and this MIT License due to copyright restrictions. 
* **Third-Party Licensed Assets:** Some assets used in the live system operate under their respective Creative Commons licenses (e.g., from Wikipedia, xeno-canto).
* **Direct Permission Assets:** Assets provided by specific organizations (e.g., Japan Bird Research Association) are used with direct permission on the live site and are strictly prohibited from redistribution.

### [CORRECTION NOTICE]
Between June 2023 and April 2026, some of these assets were inadvertently included in this repository without a clear distinction of their original licenses. We have since completely removed the file history to correct this licensing error and ensure compliance with the original terms.
As of June 2026, the only media assets officially packaged into this repository are the sample images under the CC BY 4.0 license as specified below.

## Credits (Media Assets)
### Included Sample Image Assets
The following sample images are included in this repository and are licensed under **CC BY 4.0**:
* **Sample Bird Images (`img/`):** Copyright © **A. Takenaka** - Licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/)

### Third-Party Media Assets (Required for full deployment)
The following assets are used in the live project under their respective Creative Commons licenses. To fully replicate the system, you must obtain these (or your own) assets and place them in the `mp3/` and `img/` directories.

#### Audio Assets
- **xeno-canto**: Recording by Anon Torimi - CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/)

#### Image Assets (Wikipedia / Wikimedia Commons)
- **Japanese Green Woodpecker (Aogera)**: Photo by Cory - CC BY-SA 3.0 (https://creativecommons.org/licenses/by-sa/3.0)
- **Common Cuckoo (Kakko)**: Photo by Tim Peukert - CC BY-SA 3.0
- **Chinese Hwamei (Gabicho)**: Photo by Charles Lam - CC BY-SA 2.0 (https://creativecommons.org/licenses/by-sa/2.0)
- **Lesser Cuckoo (Hototogisu)**: Photo by Ron Knight from Seaford, East Sussex, United Kingdom - CC BY 2.0 (https://creativecommons.org/licenses/by/2.0)
- **Asian Stubtail (Yabusame)**: Photo by M.Nishimura - CC BY-SA 3.0

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
This license applies **only to the source code** within this repository. 
All media assets (audio, spectrograms, and images) used in the live version of this project are **EXCLUDED** from this MIT License.

1. **Third-Party Licensed Assets (CC BY-SA / CC BY-NC)**: Some assets are used under Creative Commons licenses (e.g., from Wikipedia, xeno-canto). These are provided by their respective creators and are subject to their own original licenses.
2. **Private/Provided Assets**: Assets provided by specific organizations (Japan Bird Research Association) or individuals are used with direct permission and are **strictly prohibited from redistribution or unauthorized reuse.**

### [CORRECTION NOTICE]
Between June 2023 and April 2026, some of these assets were inadvertently included in this repository without a clear distinction of their original licenses. We have since completely removed the file history to correct this licensing error and ensure compliance with the original terms.

## Credits (Third-Party Assets)
The following assets are used under Creative Commons licenses.

### Audio Assets
- **xeno-canto**: Recording by Anon Torimi - CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/)

### Image Assets (Wikipedia / Wikimedia Commons)
- **Japanese Green Woodpecker (Aogera)**: Photo by Cory - CC BY-SA 3.0 (https://creativecommons.org/licenses/by-sa/3.0)
- **Common Cuckoo (Kakko)**: Photo by Tim Peukert - CC BY-SA 3.0
- **Chinese Hwamei (Gabicho)**: Photo by Charles Lam - CC BY-SA 2.0 (https://creativecommons.org/licenses/by-sa/2.0)
- **Lesser Cuckoo (Hototogisu)**: Photo by Ron Knight from Seaford, East Sussex, United Kingdom - CC BY 2.0 (https://creativecommons.org/licenses/by/2.0)
- **Asian Stubtail (Yabusame)**: Photo by M.Nishimura - CC BY-SA 3.0

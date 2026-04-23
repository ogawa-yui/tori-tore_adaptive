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
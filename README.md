# Parliament_Browser_4_2
----
## Before  Start...

1. We provide a static page for you to check required everything you need incl. Documentation Diagram... ： Originally used for gitlab page, but abrami canceled this task  [modellierung/index.html](modellierung/index.html).

2. In addition to the front-end presentation(just run **start.java** you will see everything), each Teilaufgabe provides test cases in test folder. 
3. The code always has the **gitlab version** as the most **trustworthy** version, since olat disk is limited.
4.  All write and delete database operations are **commented to prevent misuse**, please **check test and database directly**. Here is connection key: mongodb://PPR_WiSe24_Project_4_2_rw:QJsLyls3@ppr.lehre.texttechnologylab.org:27020/PPR_WiSe24_Project_4_2
5. If you want to identify the developer of each piece of code, always see @author in the comments and all front-end code(.ftl, .js) developed by Li Min. All other places where the author is indicated may be mislabeled, each author is only responsible for their own code(Because this scoring is based on how well the individual code is developed, laut Aufgabenblatt Der jeweilige Verdienst am Projektfortschritt bzw. am Projektergebnis fließt anteilig ein). 
6. The video file is **too large**, so please download it **manually** from **gitlab branch video** to **src/main/resources/videosLowProfile/xxxx.mp4**, now all videos are **gitignored**.
7. Same Way for all xmi files from periode20, use **src/test/java/aufgabe2/TeilD.java** download all files in folder src/main/resources/periode_20_XML
8. The daemon is set to refresh **once a day** to see if there are any new XMI-Files.
9. Menglong Ding withdrew from the group at the beginning, and the actual number of members in the group was **3**.
10. Feel free to contact us with any questions. Just click **start.java** and enjoy! Thank you for reading:)

## Aufgabe Verteilung

Li Min:  Aufgabe1.a + Aufgabe 2.0.b + Aufgabe 2.0.g + Aufgabe 3.1 + swagger document + corresponding documentation + manual

Xinyu Zhao: Aufgabe 1.b + Aufgabe 3.2 + corresponding documentation

Jiadong Zhou: Aufgabe 1.c + Aufgabe 2.0.x + Aufgabe2.1 + corresponding documentation + gitlab page + test

## Tech-Stack 

Architektur: MVC, Model + View + Controller

Gantt Diagramm: Mermaid.js

Markdown-Editor: Typora, Sublime Text, etc ...

Frontend: JavaScript, d3.js, jQuery, FontAwesome

Backend: Java, Javalin, Jsoup, ffmpeg

DB: MongoDB

NLP: 

​	**spaCy**

​	Docker-Image: docker.texttechnologylab.org/textimager-duui-spacy-single-de_core_news_sm:0.1.4

​	Remote-URL: http://spacy.lehre.texttechnologylab.org

 

​	**GerVader**

​	Docker-Image: docker.texttechnologylab.org/gervader_duui:1.0.2

​	Remote-URL: http://gervader.lehre.texttechnologylab.org

 

​	**ParlBert**

​	Docker-Image: docker.texttechnologylab.org/parlbert-topic-german:latest

​	Remote-URL: http://parlbert.lehre.texttechnologylab.org

 

​	**WhisperX**

​	Docker-Image: docker.texttechnologylab.org/duui-whisperx:0.2

​	Remote-URL: http://whisperx.lehre.texttechnologylab.org



Docs: Java Docs, swagger.io, LaTeX

----

## License

```plaintext
MIT License

Copyright (c) 2025 Jiadong Zhou, Li Min, Xinyu Zhao

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

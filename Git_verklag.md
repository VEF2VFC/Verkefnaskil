# Git verklag

Til að vinna skipulega í verkefnum þarf að sækja áfangageymsluna af Github. Til þess er best að nota GIT.

* Á *Linux* og *Mackintosh* er GIT innbyggt í kerfið. 
  * Til að nota GIT er hægt að opna **Terminal** sem er innbyggt skipanaforrit 
  * Athugaðu hvort það sé til með því að skrifa `$ git --version `
* Á *Windows 10* notum við forritið [**Git Bash**](https://git-scm.com/)

* Opnið forritið Git Bash / Terminal
  * Skráðu þig sem **&quot;--global&quot;** notanda 
```
$ git config --global user.name "Johndoe"

$ git config --global user.email johndoe@example.com
```
* Johndoe = þitt **"notandanafn"** á Github (_með gæsalöppum_)
* Þitt tölvupóstfang sem þú notar á Github

[https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)


  * Við speglum áfangageymsluna **"Clone Repository"** og vinnum með gögnin í geymslunni staðbundið (local)
  * Það er hægt að skrifa kóða beint í skjöl í Github geymslum, munið að vista skráninguna með _"Commit"_ 
  * Aðeins er hægt að skoða vefsíður í vafra (_browser_) staðbundið (_local_)  
  * Síðan er verkefnum skilað með því að velja **"Git Commit"** og **"Git push"**  í _Visual Studio Code_ forritinu eða _Git bash_
  * Þegar yngri útgáfa skjals er í víðværri (_remote_) geymslu þá þarf að sækja það með skipuninni **"Git pull"**
  * Ef maður er ekki viss hver staðan er þá er tjékkað á stöðunni með **"Git status"**. 
  * [Allt um GIT má lesa hér](https://vefhonnun.github.io/verkstjorn/index.html)
  * [Uppsetning staðbundinnar "local" áfangageymslu](https://youtu.be/PPwpF6yTX3Y) Skjáfyrirlestur á Youtube

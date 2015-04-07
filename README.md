# DonkeyKong

A little game created by Marco Gribaudo and Pietro Piazzolla of Politecnico di Milano for the course called "Computer Graphics" in 2012.
**I modified this software to extends funcionalities, like movement, interactions and i created a sprite of Donkey Kong and another one for the princess.**

**This software requires a library** created by Marco Gribaudo and Pietro Piazzolla **that i can't release because explicitly forbidden by the authors.**

I decided to realese this ".c" file, because i worked on this for many days and i implemented lots of features respect the original version distributed during the course in 2012.

**Obviously, you can't download this and compile.**

Sorry guys, but the authors wrote in the gaSim sources this: "To be used only for the Computer Graphics course". I can't release the gaSim library.

# Images

# Instruction Dev-C++ on Windows XP
1. Install Dev-C++ 5.0 beta 9.2 (4.9.9.2) [HERE](http://sourceforge.net/projects/dev-cpp/files/Binaries/Dev-C%2B%2B%204.9.9.2/devcpp-4.9.9.2_setup.exe/download?use_mirror=switch)
2. Create a new Project (multimedia - glut - C)<br>
![alt tag](http://www.stefanocappa.it/publicfiles/Github_repositories_images/DonkeyKong/1-devcpp-new-project.png)<br>
![alt tag](http://www.stefanocappa.it/publicfiles/Github_repositories_images/DonkeyKong/5-devcpp.png)
2. Add the libraries from this repository [HERE]()
3. Click on "Project" menu -> "Project Option" -> "Parameter Tab".
4. Select "add Library or object" option
5. Select "libpthreadGC2.a" ([More info](http://stackoverflow.com/questions/2119779/how-to-use-pthread-library-in-devc
)) and "libglew32.a" files from installation directory of Dev-C++ directory. For example: C:\Dec-Cpp\lib\libpthreadGC2.a and C:\Dec-Cpp\lib\libglew32.a.<br>
![alt tag](http://www.stefanocappa.it/publicfiles/Github_repositories_images/DonkeyKong/2-add-linker.png)<br>
![alt tag](http://www.stefanocappa.it/publicfiles/Github_repositories_images/DonkeyKong/3-scelta-libreria.png)
6. Compile <br>
![alt tag](http://www.stefanocappa.it/publicfiles/Github_repositories_images/DonkeyKong/4-compilato.png)
7. Run <br>
![alt tag](http://www.stefanocappa.it/publicfiles/Github_repositories_images/DonkeyKong/6-in-esecuzione.png)
<br>
##License

   Copyright 2013-2015 Politecnico di Milano, Stefano Cappa

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

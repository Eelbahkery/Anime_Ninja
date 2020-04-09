# Anime_Ninja
 A program to download 1080p anime episodes with one click(with arabic subtitles).
 <br><br>
 ![screenshot](https://user-images.githubusercontent.com/54943086/78883666-166b5680-7a5a-11ea-8e03-78b3e9cb4195.png)
### Requirements :
 1- Operating System : Windows only. <br/>
 2- Google chrome must be installed.

### How to install :
####  Easy Way :
 * Download the exe file from here [Anime Ninja](https://github.com/khalidwaleed0/Anime_Ninja/releases)
 * When you download the exe file there is no installation needed.
####  Hard Way :
 * If you want to run the code on your IDE or make your own jar file, you should :
   * Put chromedriver.exe in the resources.
   * add selenium libraries to the build path.
   * Choose to compile the program using jre 1.8 as for some reason it is the only version that works.
   * Run your IDE as admin so that the program runs with admin priviliges.(It is needed when the porgram checks whether or not chrome is installed and when it extracts chromedriver.exe and downloadLocation.txt in program files).
   * Class (scraper) contains some arabic string make sure your ide uses UTF-8 so that it can read it properly.
### How does the program work ?
 It uses selenium libraries and chromedriver to scrap the website [animesanka.net](https://www.animesanka.net).

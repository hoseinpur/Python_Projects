<a name="readme-top"></a>


[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="Images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Python Projects 🐍</h3>

  <p align="center">
    easy to advanced Python project ideas to jumpstart your Python journey!
    <br />
    <a href="https://github.com/hoseinpur/Python_Projects"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/hoseinpur/Python_Projects">View Demo</a>
    ·
    <a href="https://github.com/hoseinpur/Python_Projects/issues">Report Bug</a>
    ·
    <a href="https://github.com/hoseinpur/Python_Projects/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#project-1">Project 1: Calendar Convertor</a>
      <ul>
        <li><a href="#example1">1. Converting Hijri date to Gregorian date</a></li>
        <li><a href="#example2">2. Converting Gregorian date to Hijri date</a></li>
        <li><a href="#example3">3. Converting Jalali date to Hijri date</a></li>
      </ul>
    </li>
    <li><a href="#project-2">Project 2: IMDB Telegram Bot</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

There are many ways to enhance your Python Knowledge, but to the best of my knowledge, doing random Python projects can push you to learn new topics and use the knowledge you have acquired before. I suggest two projects for starting with, according to your own Python knowledge they can be easy or advanced for you. However, to those who have an intermediate Python skills, one project is easy and another one advanced.

_The list of projects and README will be updated accordingly._

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- PROJECTS -->
## Project 1: Calendar Convertor

To all my fellow Iranian friends, this simple project is made specifically for you. You need to write a Python project that converts dates: Gregorian (میلادی) > Hijri (هجری) > Jalali (شمسی). This project should be in form of a Python library, registered in Python libraries so that everyone could download and install. 

*PLEASE consider the below points and hints:*


* After you finish writing the library, put it on https://pypi.org/ so that it can be installed with ```pip install your_calendar_lib``` 

* Be sure about exception handling in your code! (empty input, input with different datatype, zero division, different number of input argument, etc.) 

*How to name your library:*

* The first two letters of your last name + The first two letters of your FirstName + 'date'+ 'converter' Example: First Name: Draco, Last Name: Malfoy, library name: drmadateconverter 

* If the library name exists in the https://pypi.org/, add a random two-digit number to the end of it. library name: elghdateconverter12 

* Name of functions and number of inputs have to be same as mentioned functions, exactly! 

*FINALLY:*

* Write a README of how to install your library and put it along with the codes in your GitHub. 



*Methods and Functions:*

### 1. Converting Hijri date to Gregorian date

```
your_calendar_lib.hijri(Year, Month, day).hijri_to_gregorian()

```

Example:

```
your_calendar_lib.hijri(1444, 08, 07).hijri_to_gregorian() out: (2023,02 ,28 ) #Gregorian,output type: tuple!

````

### 2. Converting Gregorian date to Hijri date

```
your_calendar_lib.gregorian(Year, Month, day).gregorian_to_hijri()

```

Example:

```
your_calendar_lib.gregorian(2023,02 ,28 ).gregorian_to_hijri() out: (1444, 08 , 07 ) #Hijri,output type: tuple!

```

### 3. Converting Jalali date to Hijri date

```
your_calendar_lib.jalali(Year, Month, day).jalali_to_hijri()

```

Example:

```
your_calendar_lib.jalali(1401, 12, 09).jalali_to_hijri() out: (1444, 08, 07) #Hijri,output type: tuple!

```

and many more methods should be included.


## Project 2: IMDB Telegram Bot

For this project, you need to create a Telegram bot for searching Movies in the IMDB API! 


*The bot should have these Steps when you start it:*

- [ ] Start
- [ ] Search a phrase  
- [ ] Show the list of movies, based on your search
- [ ] Select the desired movie 
- [ ] Show the selected movies information
    - [ ] English
    - [ ] Persian


*Project Guides:*

* You can find the API's here: [IMDB API](https://imdb-api.com/)    
* Before finding APIs, you have to register in the website [IMDB](https://imdb-api.com/)
* Use [Python Server](https://www.pythonanywhere.com/) as your server! _just a suggestion_
* [Sample Bot](https://t.me/GoodIMDbOT)
* UI and other options of your robot does not need to look like this robot. 
* How to name your bot: ```LastName+FirstName+imdb+bot``` 


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make the projects better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Soho - [@soho.codes](https://instagram.com/soho.codes) - soho.codes@gmail.com

Project Link: [Python Projects](https://github.com/hoseinpur/Python_Projects)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## References

[Filoger](http://filoger.com) 



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/badge/CONTRIBUTORS-0-brightgreen
[contributors-url]: https://github.com/hoseinpur/Python_Projects/graphs/contributors
[forks-shield]: https://img.shields.io/badge/FORKS-0-informational
[forks-url]: https://github.com/hoseinpur/Python_Projects/network/members
[stars-shield]: https://img.shields.io/badge/STARS-0-blue
[stars-url]: https://github.com/hoseinpur/Python_Projects/stargazers
[issues-shield]: https://img.shields.io/badge/ISSUES-0-yellow
[issues-url]: https://github.com/hoseinpur/Python_Projects/issues
[product-screenshot]: Images/screenshot.png
[Python-url]: https://www.python.org/downloads/
[JupyterNotebooks-url]: https://jupyter.org/install

# Touri-The-Museum-Tour-Guide-Robot
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
<!--     <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li> -->
    <li><a href="#contact">Contact</a></li>
<!--     <li><a href="#acknowledgements">Acknowledgements</a></li> -->
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This my Capstone Project for UofT ECE496 and it was originally done during the period of 2019 Sep - 2020 Apr.

Museums are a hub of knowledge and history, defining the culture of a period and a people.
However, it is seen that the number of museum visitors, hence the number of people learning
from this hub of knowledge, has been in a steady decline since 1982 in North America[1]. This
report describes and evaluates a solution to this issue aimed at making museums more attractive
to the general public, especially young adults who have the biggest decline in visits[1].
Our group proposed the implementation of a tour guide robot, Touri - a robot that will provide
not only additional information about the displays but also tie together the narrative to provide an
overarching view of the displays - why they are in that room, why specific displays are next to
each other, etc. This narrative will not only make the visit more fun but also more memorable for
the visitors, encouraging them to take advantage of these hubs of knowledge.
The robot will be fully autonomous once the tour has started. This is to provide a more
immersive experience for the visitor to make the entire visit more memorable.
The group decided to go with buying a robot kit rather than building everything from scratch.
The main navigation will be done with line following with basic obstacle avoidance in place so
Touri should not run into other people or objects in its path. There will also be distance
monitoring in place via a camera so Touri can adjust its speed according to the visitors on tour.
All these functionalities allow Touri to give a more interactive experience to the visitors which in
turn will encourage more visitors to the museums.


### Built With

* [Python](https://www.python.org/)
* [OpenCV](https://pypi.org/project/opencv-python/)
* [Google NLP API](https://cloud.google.com/natural-language/docs/reference/libraries)
* Linux
* Raspberry Pi

<!-- CONTACT -->
## Contact

Zihan (Aaron) Zhao[Lead] - zzh.zhao@mail.utoronto.ca

Jingfeng (Eric) Chen - jingfeng.chen@mail.utoronto.ca

John Courtney - jcourtne@tcd.ie

Momin Mehmood - s1406615@sms.ed.ac.uk


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/aaron-zhao
[product-screenshot]: images/screenshot.png

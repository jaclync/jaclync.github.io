---
layout: projects
title: projects
permalink: /projects/
---

<!-- <ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

      <p class="rss-subscribe">
        {{ post.content }}
      </p>
    </li>
  {% endfor %}
</ul> -->

<table width="100%" border="0" cellspacing="10" cellpadding="2">
  <tr>
    <td colspan="2">
      <div class="table-header" align="center">
        <p>
          <strong>Street Sweep - San Francisco Parking</strong>
          <br/>
          url/ <a href="https://itunes.apple.com/us/app/street-sweep-san-francisco/id1170815127?l=zh&ls=1&mt=8">App Store </a>
          <br/>
          w/ Tony Cosentini
          <br/>
          2014 spare time
        </p>
      </div>
    </td>
  </tr>
  <tr>
    <td width="350">
      <div class="image-container">
        <img src="/images/projects/streetsweep_1.png" alt="Climbly filters" width="170" />
      </div>
      <div class="image-container">
        <img src="/images/projects/streetsweep_2.png" alt="VGA_Animation" width="170" />
      </div>
    </td>
    <td>
      <p>
        Living in San Francisco with a car and street parking is not easy.
        After getting a few parking tickets from forgetting to move my car for street sweeping hours, I started doing these manually -
      </p>
      <ul>
        <li>Park where I can leave it for the longest</li>
        <li>Remember where I park</li>
        <li>Remind myself to move the car</li>
      </ul>
      <p>
        Instead of checking calendar / calculating how many days I can leave my car / dropping a pin on Google maps and SMS to myself,
        we made an iOS app that streamlines the work above.
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <div class="table-header" align="center">
        <p>
          <strong>College Tasting</strong>
          <br/>
          url/ <a href="http://rpi.climbly.com/">Climbly x RPI Beta</a>
          <br/>
          w/ Climbly team
          <br/>
          2013-2014 spare time
        </p>
      </div>
    </td>
  </tr>
  <tr>
    <td width="350">
      <p align="center">
        <img src="/images/projects/climbly_rpi_header.png" alt="Climbly header" width="200" />
      </p>
      <p align="center">
        <img src="/images/projects/climbly_filter.png" alt="Climbly filters" width="150" />
      </p>
    </td>
    <td>
      <p>
        Before coming to the Bay Area for grad school, I asked around and got helpful insights from connections I had before making a decision where to go.
        Other Climbly members had similar experiences. What if there is a platform where reaching out to people at school is easy, like college tasting?
        We developed a web app using Google App Engine that allows students to schedule an online chat with an "ambassador" from the school.
        Filters are helpful for finding ambassadors with specific backgrounds.
        We collaborated with RPI to launch our pilot, with about 10 ambassadors to answer questions from students and applicants.
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <div class="table-header" align="center">
        <p>
          <strong>Safe Driving</strong>
          <br/>
          Digital Circuit Lab
          <br/>
          w/ Allen Chen, Peter Lin
          <br/>
          Summer, 2007
        </p>
      </div>
    </td>
  </tr>
  <tr>
    <td width="350">
      <p align="center">
        <img src="/images/projects/project_DCLab_car.JPG" alt="DC_SafeDrivingCar" width="300" height="225" />
      </p>
      <p align="center">
        Completed automatic safe-driving car
      </p>
      <p align="center">&nbsp;</p>
      <p align="center">
        <img src="/images/projects/VGA_ani.gif" alt="VGA_Animation" width="300" height="224" />
      </p>
      <p align="center">Sensing process on VGA screen<br />
        Red, external circle: max. 80 cm<br />
        Red, internal circle: min. 10 cm <br />
        White circle: detected distance <br />
        (360 degree fully rotating sensor)
      </p>
    </td>
    <td>
      <p>
        After the intriguing course of Switching Circuits and Logic Design, I took the Digital Circuit Lab in the following summer. We began from getting familiar with Verilog HDL language through three experiments:
      </p>
      <ol>
        <li>Traffic light</li>
        <li>256-bit RSA encryption/decryption algorithm</li>
        <li>Digital audio player/recorder</li>
      </ol>
      <p>To add the excitement, we built a miniature safe-driving automatic car in the final project. Controlled by our ALTERA digital board, the car is able to avoid the obstacles such as walls or boxes according to the distance data provided by the infrared sensor mounted on the car.</p>
      <p>During the building and testing, we have encountered tough problems like the power supply of FPGA board when the car is moving. Therefore, we have designed a battery set for FPGA board that not only supplies power constantly by the use of capacitor but also protects the FPGA board from illegal current and external by the use of relay and BJT.</p>
      <p>Another problem arises when our infrared sensor only detects distance in a single direction while we need it to obtain the distance data from every direction. Utilizing more sensors can be one solution, yet we decided to use stepper motor to rotate the infrared sensor on the top of car in order to minimize the cost. After several tuning and testing of every equipment, our car was running safely !</p>
      <p>
        <strong>(In Mandarin) [<a target="_blank" href="/projects/DCLab_project.ppt">ppt</a>] (with animation !) [<a target="_blank" href="/projects/DCLab_project.pdf">pdf</a>]
        </strong>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <div class="table-header" align="center">
        <p>
          <strong>Who Moved My Bike ?</strong>
          <br/>
          Introduction to CS
          <br/>
          w/ Alex Ho, Ashley Hsueh
          <br/>
          Spring, 2006
        </p>
      </div>
    </td>
  </tr>
  <tr>
    <td width="350px">
      <p align="center">
        <img src="/images/projects/CS_project_bikesensor.jpg" alt="BikeSensor" width="300" height="210" />
      </p>
      <p align="center">Sensor on the bicycle</p>
      <br/>
      <p align="center"><img src="/images/projects/CS_project_sensor.PNG" alt="Sensor" width="300" height="218" /></p>
      <p align="center">Transmitter on the bicycle </p>
      <br/>
    </td>
    <td>
      <p>
        <span>Inspired by my loss of bicycles on the campus several times, we decided to locate a bicycle by tracking its movement.
        </span>
      </p>
      <p><strong>Procedures:</strong></p>
      <ol>
        <li>Install the sensor on the bike. Connect the sensor to a 1.5V battery set and the chip of wireless sending node loaded with recording program.</li>
        <li>Connect the wireless receiving chip loaded with distance-computing program to a notebook. Turn on the software- Realterm : Serial Capture Program which enables us to show how long the bike has been going through.</li>
        <li>Ride the bike away. Upon the moment we find that the figure on the screen is changing, we are informed that the bike has been moved by somebody and the distance can be derived from the data we have collected.</li>
      </ol>
      <p><strong>Tools:</strong></p>
      <ol>
        <li>Professional stopwatch for bicycles (cyclocomputer)</li>
        <li>Wireless Sensor Nodes (transmitter/receiver)<br />
        (for mass production it may cost less than 300 NT dollars)</li>
        <li>Laptop</li>
        <li>IAR Embedded Workbench IDE</li>
        <li>Realterm: Serial Capture Program 1.99.0.34</li>
      </ol>
    </td>
  </tr>
</table>

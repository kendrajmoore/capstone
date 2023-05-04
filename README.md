
<a name="readme-top"></a>
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/kendrajmoore/capstone/edit/main/README.md">
    <img src="https://i.ibb.co/QP2QXhB/Pngtree-cute-green-small-plant-aloe-4651505.png" alt="Logo" width="200" height="200">
  </a>

  <h3 align="center">Internet-of-Things Environmental Monitoring for Soil Sensing</h3>

  <p align="center">
    An IoT Plant Monitoring System that allows you to review your plants health stats from anywhere in the world using an ESP32, InfluxDB, MQTT, and Grafana.
    <br />
    <a href="https://github.com/kendrajmoore/capstone/edit/main/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://grafana.smartplant.live/d/livedata/plant-dashboard">View Demo</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://i.ibb.co/5W6v0Jz/Screenshot-2023-04-30-at-3-17-16-PM-1.png)

Plant monitoring has become an increasingly prominent environmental measurement in climate change, water resource forecasting, land stability, and crop management. Current technologies in soil monitoring are used to help farmers understand their plant health and make decisions about how to care for their crops. These existing technologies, however, rely on proprietary sensors and lack the ability to onboard or customize new types of sensors. The platform will offer

1. Seamless sensor integration
2. Storage of time series data
3. monitoring and visualizations on live data. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![React][React.js]][React-url]
* [![Node-Red][Node-Red]][Node-url]
* [![InfluxDB][InfluxDB]][Influx-url]
* [![Grafana][Grafana]][Grafana-url] 
* [![Mosquitto][mosquitto-shield]][mosquitto-url]
* [![Arduino][Arduino]][Arduino-url]
* [![Digital Ocean][Digital Ocean]][Digital-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To create this project you need a 
1. Wifi enabled Arduino device (ESP32, ESP8622) 
2. Linux device (Raspberry Pi, AWS, Digitial Ocean)
3. DHT11 Temperature and Humidity Sensor
4. Capacitive Soil Sensor
5. Jumper Wires
6. Breadboard


### Installation

1. Connect the DHT11 and Capacitive Soil Sensor to your device. 

[![Device][device-screenshot]](https://i.ibb.co/5W6v0Jz/Screenshot-2023-04-30-at-3-17-16-PM-1.png)


1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Random Nerd Tutorials](https://randomnerdtutorials.com/)
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: https://i.ibb.co/5W6v0Jz/Screenshot-2023-04-30-at-3-17-16-PM-1.png
[device-screenshot]: https://i.ibb.co/z474hY4/Screenshot-2023-04-26-at-11-39-41-AM.png
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Node-Red]: https://img.shields.io/badge/Node--Red-8F0000?style=for-the-badge&logo=nodered&logoColor=white
[Node-url]: https://nodered.org/
[Arduino]: 	https://img.shields.io/badge/Arduino_IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white
[Arduino-url]: https://www.arduino.cc/en/software
[InfluxDB]: https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=InfluxDB&logoColor=white
[Influx-url]: https://vuejs.org/
[Digital Ocean]: https://img.shields.io/badge/Digital_Ocean-0080FF?style=for-the-badge&logo=DigitalOcean&logoColor=white
[Digital-url]: https://www.digitalocean.com/
[Grafana]: https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white
[Grafana-url]: https://grafana.com/
[license-shield]: https://img.shields.io/badge/License-MIT-yellow.svg
[license-url]: https://opensource.org/licenses/MIT
[mosquitto-shield]: https://img.shields.io/badge/mosquitto-%233C5280.svg?style=for-the-badge&logo=eclipsemosquitto&logoColor=white
[mosquitto-url]: https://mosquitto.org/

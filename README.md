<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Apache-2.0 License][license-shield]][license-url]

<!-- PROJECT TITLE -->
<br />
<div align="center">
<h3 align="center">Robonomics ROS 2 Wrapper</h3>

<p align="center">
    Python packages with simple wrapper of Robonomics parachain functions for Robot Operating System 2
</p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About Project</a>
      <ul>
        <li><a href="#project-structure">Project Structure</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation-and-building">Installation and Building</a></li>
        <li><a href="#configuration">Configuration</a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Usage</a>
        <ul>
        <li><a href="#testing-with-turtlesim">Testing with Turtlesim</a></li>
        <li><a href="#programming-your-wrapper-implementation">Programming Your Wrapper Implementation</a></li>
        </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About Project

This ROS 2 Python packages are dedicated to wrapping [**aocomputer**](https://cookbook_ao.g8way.io/) parachain API
provided by [**ao-python-interface**](https://github.com/kimtony123/ao-python-client)
into nodes of ROS 2. aocomputer is a decentralized compute enviroment that allows users to create perform all kinds of compute.

The goal of the project is to provide ROS 2 developers with a convenient way to integrate their robots or devices
with aocomputer. The logic behind the integration of a robotic device is that a unique address is created
for it in aocomputer, which is used to control the device or receive its telemetry.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Project Structure

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

Make sure you have the following software installed:

- Linux OS distribution (tested on [Ubuntu 22.04.4](https://releases.ubuntu.com/jammy/))
- ROS 2 distribution (tested on [Humble version](https://docs.ros.org/en/humble/Installation.html))
- [Python 3](https://www.python.org/downloads/) (tested on 3.10.12)

- Project specific Python modules can be installed via:
  ```shell
  pip install -r requirements.txt
  ```

For testing:

- Turtlesim package for your ROS2 version. For Humble:
  ```shell
  sudo apt install ros-humble-turtlesim
  ``
  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

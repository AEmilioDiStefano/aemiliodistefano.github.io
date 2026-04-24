![host-and-port](images/emilio-picture.png)

## A. Emilio DiStefano

Hi, I'm Emilio - a results-driven software engineer dedicated to the development of effective, efficient, low-cost robotics and embedded systems solutions.  Here are some of my projects: 

<br>  
<br>  

# Swarm Control Core  

<p align="center">
  <img src="images/remote_operation_GIF.gif" alt="Remote operation demo"> <img src="images/FPV_gif.gif" alt="Virtuan FPV demo">
</p>

### [swarm_control_core](https://github.com/AEmilioDiStefano/swarm_control_core)

**Swarm Control Core** is a ROS2 package that allows the user to control heterogeneous swarms of robots.  It includes an interactive browser UI that allows users to control swarm robots while seeing from their persoective via integrated, USB, serial, and other camera types.  The package is optimized for low-latency FPV on a local network.  It includes basic security features and automated camera integration which scrapes camera metadata and sets a camera profile that can be used for each individual robot regardless of camera type.  

**Swarm Control Core** acts as a baseline for **Swarm Control Pro**, which is a non-public proprietary package that includes a wide variety of additional features such as remote operation capabilities from a remote browser, robuts security features, and automated onboarding of new build types (ground based, aerial, etc) to heterogeneous robot swarms.  **Swarm Control Pro** is optimized for use in mission-critical use-cases such as military, law enforcement, emergency response/rescue, and other highly sensitive applications.  For more information on the non-public proprietary **Swarm Control Pro** package, contact **[emilio@vitruvian.systems](emilio@vitruvian.systems)** 

<br>  
<br>  

# FPV Router
<p align="center">
  <img src="images/FPV-router.png" alt="FPV Router">
</p>

### [FPV Router](https://github.com/AEmilioDiStefano/FPV_router)

This Pi-powered FPV router uses a single-board computer with a full Linux operating system for **ultra-customizable routing**.  Optimized for **low-latency video transfer for FPV robotics operations**, this router outperforms even high-end travel router models at a price comparable to that of a mid-range travel router.  Use this router to control robot swarms, or customize it to virtually any end that you can think of.

This project’s source code is licensed under the PolyForm Noncommercial License 1.0.0, which allows personal and noncommercial use but prohibits commercial use without obtaining a separate commercial license from me or my company.

<br>
<br>

# Differential Drive Robot Build Tutorial (Author) 

<p align="center">
  <img src="images/hide-and-seek-GIF.gif" alt="Robot tutorial demo">
</p>

![host-and-port]() 
### [Robot Build Tutorial](https://github.com/AEmilioDiStefano/ros2_ws_minimal)

This minimal (headless) version of the **Legion Control Workspace** contains all of the software needed to build and control one or several robots from a remote location.  While the **Legion Control Workspace** is designed for laptops or control computers, **Legion Control Workspace Minimal** is designed to be cloned onto the robots themselves.  Included is a comprehensive tutorial complete with visual and written build instructions to build ROS2 robots ready for autonomous functions for under $120 USD in materials (each). 

This project’s source code is licensed under the PolyForm Noncommercial License 1.0.0, which allows personal and noncommercial use but prohibits commercial use without obtaining a separate commercial license from me or my company.

<br>  
<br>  

# MemoryBot (Education) 
![host-and-port](images/MemoryBot-screenshot-2.png)
### [MemoryBot](https://github.com/AEmilioDiStefano/MemoryBot)

The MemoryBot project is a system for seamless access to information regardless of internet accessibility.  Tell MemoryBot anything from the melting point of potassium to the name of your fourth cousin's fifth daughter, and MemoryBot will remember it for later.  No more forgotten birthdays, no more awkwardly asking questions which you should already know the answer to, and no more depending on the internet for knowledge - accumulate your own here.  

Also, simulate necromancy with the "Talk to dead people" function.  Have you ever wanted to interview Benjamin Franklin on what he would think of the modern world?  MemoryBot's "Talk to dead people" function can make that happen.  The system is designed for the easy addition of new entities.  Just add a JSON file of question-answer (key-value) pairs and make some minor code adjustments to converse with the historical figure or fictional character of your choice.  JSON files with question-answer(key-value) pairs can be written manually or generated from an AI services like ChatGTP.  **As more questions and answers are added to each entity's JSON memory file, the entity's dialogue will become more accurate and convincing**.  Three of these such entities are included in this program for inspiration. 

This program is written in C++ and uses an **inverted index data structure** along with a **linear merge count algorithm** to find the best answers to questions asked by the user.  The system uses a local JSON data store and does not require an internet connection to run.  **Large conversational data sets can be stored locally for each agent in order to achieve a high level of precision in answering questions**.  The application is lightweight and can **run on very limited hardware**.  The final goal of this project is to run it on an autonomous mobile robot as an energy-efficient solution for communication with humans using locally stored data for usbability in **situations where signal communication is unreliable or impossible**. 

Here is a video showcasing the functionality of the [MemoryBot system](https://www.youtube.com/watch?v=cjq_WKRvxD4).

<br>
<br>

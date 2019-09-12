---
layout: default
---

<h1 id="about">About Me </h1>

I am a master student at University of California, San Diego majoring in Computer Science. Previously, I received  a B.E. in Automation (Control Engineering) at Zhejiang University. I used to be a software development intern in Mobile Robot Department at **[Hikvision](http://www.hikvision.com/en/)**. I also worked as a research assistant with **[Prof. Tao Gao](http://www.stat.ucla.edu/~taogao/)** in **[VCLA Lab](http://vcla.stat.ucla.edu/index.html)** at UCLA and **[Prof. Jiangang Lu](https://person.zju.edu.cn/en/lujg)** at my home institution, Zhejiang University.

<br><br>

Now I am actively seeking for Summer 2020 SDE internships.  

---

<h1 id="ongoing">Work Experiences</h1>
<h2>Hangzhou Hikvision Digit Technology Co., Ltd</h2>

*Software Engineer Intern, Mobile Robot Department*

The goal of my team is to analyze a new type of LiDAR and built processing tools for raw point cloud data. In order to provide upper management tools, I developed a internal dashboard web application from stretch for rendering point cloud images and parameters based on MVC principles. I created the front-end with D3.js and React.js for compressive data visualization, and built the back-end using Node.js and Express with MongoDB. To provide limits of authorities, I designed an authentication API using JWT (JSON Web Tokens). The website was used by many teams to manage their progress and saved them much time from directly access to the raw point cloud data.

<br><br>

I also did some supportive work, including building a point cloud preprocessing pipeline for denoising and implementing SURF and SIFT feature detection algorithms, using C++ and PCL (Point Cloud Library).

---

<h2>University of California, Los Angeles</h2> 

*Research Assistant, Center for Vision, Cognition, Learning and Autonomy*

Our team worked on build a model-based trajectory optimization library using large-scale nonlinear programming. I used the physical engine Mujoco to provide real dynamic and kinematic constraints, and used the nonlinear optimizer IPOPT to provide large-scale data-driven optimization. Then I built a data visualization module that can interactively render 3D trajectory animations using C++ and OpenGL.

<br>

<br>

It's a short-cycle and iterative development project, so we used C++ best practices while coding. In order for the maintainability and scalability of the whole system, I wrote unit test using GTest/GMock framework in C++ with rigorous practices to maintain test coverage over 90%. Working with a large code base, one challenge was the memory leak and the poor performance. So I employed profiling data to fix memory leaks, and optimized the calculation of Jacobian Matrix and significantly improve the cache performance.



|![inverted](../assets/img/inverted.gif)|![d_inverted](../assets/img/d_inverted.gif)|![cartpole](../assets/img/cartpole.gif)|


<h2 id="previous">Selected Projects</h2>
<h3>Chest X-Ray Images Analysis to Diagnose, Evaluate and Follow up Overall Disease Change</h3>
An unexpected thoracoscopy surgery in my sophomore year, both terrifying and inspiring, still echoes in my mind. That was when I came to realize how imaging technologies could positively impact the world with the potential to save millions of lives. So I chose this project as my graduation thesis. I tried to combine chest X-ray images with modern computer-based image analysis techniques (computer vision, machine learning) to provide a model or tool for radiologists to better diagnose diseases. I used YOLO v3 as the detection model. Not like natural images, x-ray images lack generalization and well-defined edges. I employed several improvement  and designed a new training strategy, and finally improved the recall rate of Cardiomegaly to 92% and precision rate to 77%.

|![xray1](../assets/img/xray2.png)|![xray2](../assets/img/xray3.png)|

|![result](../assets/img/xray1.png)|

<h3>Robot Obstacle Avoidance System and Simulation using EKF-SLAM and VFH+ </h3>
Obstacle avoidance is an vital part for autonomous robots. In this project, we implemented VFH+ obstacle avoidance algorithm and in order to evaluate the effect, we designed a robot simulation environment using EKF-SLAM for proximity detection. Then the whole system was migrated to LabView in preparation for real cyber-physical system and achieved superior results than many benchmark metrics.

|![icp](../assets/img/icp.gif)|![slam](../assets/img/slam.gif)|

|![matlab](../assets/img/matlab.jpg)|


<h3>Vision-Based Flight Control on a Self-Built Drone </h3>
In this project, I led a team of 4 members and designed a four-motor drone, including original hardware modules and a flight control system. Then we implemented a little resource-hungry vision system on a Raspberry Pi to detect and track objects. After combining together, the self-built drone could track a slowly moving target and accomplish simple autopilot. Finally we changed our self-designed flight controller to a open source flight controller Pixhawk and conducted secondary development on it to enable our drone to accomplish more complex tasks.

|![fly](../assets/img/fly.gif)|![detect](../assets/img/detect.gif)|


<h2 id="interest">Passion </h2>
- **Music:**
I am fond of rock and folk music. I started tp play the drums at a very young age and then learned to play the acoustic guitar by accident, which is still my favorite. I performed on the New Year's Party twice with my guitar during my undergraduate period. My favorite guitar player is *Eric Clapton* and favorite song is *Hotel California (unplugged version, 1994)*.

- **Photography:**
Since I got my first digital SLR, I have fallen in love with landscape photography, which makes me love traveling too. Click **[here](./gallery.html)** to see the selected works.

- **Zoology and Ethology:**
In high school, I got access to Biology Olympiad and was so fascinated by Zoology and Ethology. I am always dreaming that one day I can get closer to these amazing creatures in the wild and make a documentary film.

- **Cooking:**
The traditional culture behind Chinese food always attracts me and I often cook for my families at home.

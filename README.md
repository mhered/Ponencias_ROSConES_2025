# ROSCon España 2025 – Companion Repository

This repository collects the code, slides, and resources accompanying my two talks presented at **ROSCon España 2025**:

* [Talk 1: ROS, LeRobot y un patito de goma](#talk-1-ros-lerobot-y-un-patito-de-goma)
- [Talk 2: Sensores creativos mirando la pela](#talk-2-sensores-creativos-mirando-la-pela)

Both sessions were part of the *Education* track and focused on making robotics and AI more accessible, creative, and affordable.

------

## Talk 1: ROS, LeRobot y un patito de goma — Robótica e inteligencia artificial accesible

📍 Barcelona, 5 November 2025 — Track: Education

### Abstract

In this talk, we explore how far a 100 € open-source robotic arm (SOARM100) and a rubber duck can take us in the journey of learning about robotics.  
From low-level direct control of servos, through model-based traditional robotics using ROS2 control and perception pipelines and then on to novel data-based approaches using imitation learning with pre-trained LeRobot models, we demonstrate how a simple, affordable setup can be a powerful educational tool when we leverage open source libraries, the **ROS** ecosystem of tools and **LeRobot**, the open AI robotics framework from Hugging Face. 

A live demo was originally planned that could not fit in the shortened 20-minute slot, however all the materials and code used for the experiments are available here for the community to reproduce.

### Highlights

- ROS 2 integration with MoveIt, Gazebo Harmonic, RViz, and OpenCV
- Application of LeRobot models for imitation learning and teleoperation
- Open-source, accessible, and replicable hardware and software
- Educational and community-oriented approach derived from projects presented at PyCamp España 2025 and PyConES 2025

### Requirements

- ROS 2 Jazzy
- MoveIt 2, Gazebo Harmonic, RViz
- Hugging Face LeRobot library
- Python 3.10+
- OpenCV

### Resources

- [About the talk](./patito/about.md)
- Slides used at ROSCon España 2025: [ROSConES25_ROS_Lerobot_patito_v1.1_ONLINE.pptx](https://1drv.ms/p/c/6d3f578aa3de1a64/EWnwXxY3nYZFtzqps1IWuUsB3WfCXBFiHg88qGFw6AZ3NA?e=ObfpTw)  (Link to OneDrive, large file)
- [Source code](./patito/code.md)
- [Notes](./patito/notes.md) including setup instructions to reproduce the demos and references and links to related projects and repositories


------

## Talk 2: Sensores creativos mirando la pela
📍 Barcelona, 5 November 2025 — Track: Education

### Abstract

Who says robotics requires expensive sensors? This talk presents three and a half real examples of creative, low-cost hardware integrations for ROS 2 robots — designed to inspire experimentation, teaching, and rapid prototyping on a tight budget.

Three case studies are presented:

1. Low-cost camera: hacking a $4 AliExpress webcam for visual perception.
2. RGB-D sensor retrofit: repurposing a second-hand Kinect 360 into a functional 3D sensor. We look at the quick and dirty and also at a fancier version to indulge better integration in our robot. 
3. Tactile sensor: turning a kitchen sponge and fridge magnets into a haptic sensor.

Each project includes open-source code, step-by-step build instructions, and ROS 2 integration examples.
 Beyond the humor and DIY spirit, the message is serious: democratizing robotics starts with accessible, open tools.

### Highlights

- ROS 2 integration (drivers, nodes, and examples)
- Documented, reproducible hardware builds
- Suited for educators, makers, and researchers with limited budgets
- Promotes creativity, sustainability, and fun in robotics

### Requirements

- ROS 2 Jazzy
- Gazebo Harmonic, RViz
- Python 3.10+
- Arduino IDE

### Resources

- [About the talk](./sensores/about.md)
- Slides used at ROSCon España 2025: [ROSConES25_Sensores_para_tiesos_v1.3_ONLINE.pptx](https://1drv.ms/p/c/6d3f578aa3de1a64/EUpYVlq8MdxCh3DpyzALr4cBstADo_7hRMHgbMS887zQxw?e=jFxI58) (Link to OneDrive, large file)
- [Source code](./sensores/code.md)
- [Notes](./sensores/notes.md) including setup instructions to reproduce the demos and references and links to related projects and repositories

------

## License and Acknowledgements

Original contributions (code, notes, etc) are provided for educational and community use under an open-source license. External resources quoted or linked from the repo are subject to their own licensing terms.

Special thanks to the [ROS2](https://www.ros.org/) and [LeRobot](https://huggingface.co/lerobot) communities, and to everyone contributing to accessible, open robotics.

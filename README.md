# ASL-Translator
Software Design Final Project (Spring 2018) code and documentation. ASL-Translator is a near real-time American Sign Language (ASL) translation tool that uses computer vision to recognize and track a user's gestures and uses a learned model to identify the ASL character most closely correlated to that gesture. For more information, see our [project website](https://utsav22g.github.io/ASL-Translator/).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

1. Clone this repo to your local machine
2. `python recognition.py` runs just the computer vision hand gesture detection
3. `python3 live_demo.py` will run the output of the CV gesture recognition comparing against a pre-trained model.

### Prerequisites

What things you need to install the software and how to install them

Run `pip install -r requirements.txt` in order to download all the prerequisites necessary to run the program

### Project Website

For a better understanding of who we are and how Signum works, see our [website](https://utsav22g.github.io/ASL-Translator/).

#### Built With

* [OpenCV](https://opencv.org/) - Computer Vision Library
* [Keras](https://keras.io) - Machine Learning Implementation
* [HTML5Up!](https://html5up.net/) - Used to generate project website

#### Contributing

Please read [CONTRIBUTING.md](Contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.
 

#### Authors

* **Isaac Vandor** - [Website](http://isaacvandor.com/)
* **Utsav Gupta** - [Website](http://github.com/Utsav22G/)
* **Diego Berny** - [Website](https://github.com/dberny)

#### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

#### Acknowledgments

Inspiration for this project comes from [ASL Gloves](http://www.olin.edu/news-events/2016/asl-gloves/) 

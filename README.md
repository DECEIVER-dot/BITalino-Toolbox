# DECEIVER-dataset
A Comprehensive Dataset of Elicited Emotions

Repository Name: MaxMSP Applications for IRCAM R-IoT Module and Experiment Annotation
Overview
This repository contains three applications developed in MaxMSP that enable direct communication with an IRCAM R-IoT module embedded in a BITalino board. The applications provide various functionalities, including biosignal data recording, Bluetooth connectivity, and interactive annotation while viewing video recordings of experiments. Please note that the software is designed to work with the MaxMSP programming environment and requires external libraries for specific functionalities.
Application 1: IRCAM R-IoT Module Data Recorder (USB)
The first application allows seamless communication via a USB connection with the IRCAM R-IoT module on the BITalino board. It lets the user record biosignal data directly into a CSV file format with two different sample rates. The recorded data is saved in its raw form without normalization or interpolation. The two available sample rates are:
Sample rate of the board: The application records data at the native sample rate of the BITalino board.
2ms sample rate: Additionally, the application provides the option to record data at a fixed 2ms sample rate.
Please be aware that the current software version does not include data normalization or interpolation. However, a future release will address this issue.
Application 2: IRCAM R-IoT Module Data Recorder (Bluetooth)
The second application builds upon the functionality of the first application but adds Bluetooth connectivity as an alternative communication method. With this application, the user can connect the IRCAM R-IoT module on the BITalino board and the computer using Bluetooth. It provides the same data recording capabilities as the USB version, but please note that motion data is not recorded with this application.
Application 3: Experiment Annotation with Video Recording (Mira and iOS)
The third application is specifically designed for interactive annotation while viewing video recordings of experiments. Developed in MaxMSP, it requires the installation of external libraries for the Mira interface, which provides enhanced interaction capabilities. Additionally, this application relies on an iOS device to run the software effectively.
Using this application, researchers or experimenters can annotate the video recordings in real-time, allowing for precise and synchronized annotation of events or observations. The interactive annotation feature provides a seamless workflow for experimental analysis and review.
For more detailed information about the Mira interface and the requirements for running this application, please refer to the Mira product page on the Cycling '74 website.
Additional Notes
Please note that all the applications in this repository are developed in MaxMSP, a visual programming environment for music and multimedia. Ensure you have the necessary MaxMSP software and dependencies to run these applications successfully.
For any inquiries or support regarding these applications, please refer to the respective application folders in this repository or contact the repository maintainer.
We hope these applications are helpful for your experiments and data recording needs. Enjoy using them!

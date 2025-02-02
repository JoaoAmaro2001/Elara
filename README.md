# Elara
*Seeing beyond vision*

## Authors
- Pedro Rocha
- Alice Oliveira
- João Amaro


## Inspiration
Despite having backgrounds in engineering and biomedical sciences, our team consists of highly motivated neuroscience students. On one hand, we are driven by the desire to understand how the brain works using neuroimaging techniques. On the other hand, we are passionate about innovation and the practical application of scientific knowledge to optimize daily life in society.

Throughout our studies, we have frequently encountered epilepsy—the fourth most common neurological condition worldwide, affecting approximately 70 million diagnosed individuals. This exposure has increased our awareness of the poor quality of life caused by ineffective treatments and frequent, often unpredictable, seizures.

At the same time, our knowledge of electroencephalography (EEG)—one of the primary methods used for diagnosing and monitoring the progression of epilepsy—and biosignals has led us to recognize an opportunity. By utilizing multiple sensors, such as eye-tracking (ET) sensors, we can positively impact the quality of life of these individuals and optimize clinical routines.

With this motivation, we felt the need to create Elara - Seeing Beyond Vision—a system consisting of a medical device that integrates both EEG and ET technology into a pair of smart glasses, along with machine learning algorithms embedded in a digital application. This system offers a comfortable and cost-effective solution for continuously and remotely monitoring epilepsy.

## What It Does
Elara collects and records both brain electrical activity and various characteristics of eye movements through its smart glasses. This is made possible by the presence of four active EEG sensors, located on each temple of the glasses, as well as a camera and an infrared sensor positioned in the lenses.

The placement of these sensors is strategically designed to detect both signals:

EEG electrodes are positioned at the temporo-frontal junction on each side—areas frequently associated with epileptic foci.
Cameras and infrared sensors are placed medially, directed toward both eyes.
Additionally, the digital application will allow real-time visualization of this data. In the future, it will also:

Send alerts when abnormal activity patterns are detected (via trained algorithms).
Store medical history.
Connect patients with doctors and family members.
Control specific functionalities of the glasses (e.g., inducing vibrations when anomalous states are detected).

## Build
For now, the prototype will be built using an Arduino Due as the base.

EEG sensors, attached to the temples of the glasses, and the camera, integrated into the lenses, will be connected via cables to signal processing modules for EEG and video/image processing, embedded in the Arduino.
These modules already allow real-time data visualization as they include an integrated screen.
This will serve as our initial setup. As opportunities arise, we may explore alternative technologies such as Raspberry Pi, which offers advantages due to its higher RAM and CPU capacity.

Later, the Arduino will transmit data to a smartphone via Bluetooth, where the information can be displayed in the app. The data will be stored in the cloud whenever seizures or other complications occur—or whenever the user desires.

## Possible Challenges
One of the main challenges will be efficiently integrating all components in a compact and user-friendly manner. Additionally, we need to carefully design the best way to present the data in the digital application.

However, after conducting in-depth research, we are motivated and optimistic about the feasibility of our idea.

## What's Next for Elara?
In the future, we envision Elara as a valuable system that can be applied to other clinical conditions, such as depression.

Additionally, it could be beneficial for anyone—for instance, in reducing road accidents by accurately detecting drowsiness. This could be achieved by identifying lower-frequency brain activity and detecting eye closure patterns.

Furthermore, Elara could also be used for neuromarketing consultancy, providing valuable insights into consumer behavior.

\# EndoFrameCapture



A lightweight Java Swing tool for real-time webcam preview and static frame capture using OpenCV.

This project is an isolated prototype that will later be integrated into a medical imaging system.



\## Features

\- Live webcam preview

\- Frame capture with one click

\- Images saved locally to `/images`

\- Simple Swing interface (first version)

\- OpenCV-based camera integration



\## Requirements

\- Java 11+

\- OpenCV 4.x

\- Any standard USB webcam



\## Running

1\. Download OpenCV and include the `opencv-\\\*.jar` in your classpath.

2\. Ensure the native libraries (`opencv\\\_java\\\*.dll`) are accessible via `java.library.path`.

3\. Run the `Camera` class:



```bash

java -cp .;opencv-4120.jar com.conectivida.endoscopy.project.Camera



\\## Notes



This is the first functional prototype.

Upcoming improvements include:



\* MigLayout
\* Thumbnail generation
\* Image deletion
\* 800×600 forced camera resolution









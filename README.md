Blue Air Drawing Canvas

A demo project using Python and OpenCV to draw in the air by tracking a blue object. The program captures the movement of a blue object in real-time and translates it into digital strokes on a virtual canvas.

Demo

Video demonstration with music is available in the demo folder or on LinkedIn.

Features

Tracks blue objects (cap, marker, tape on finger)

Real-time drawing

Clear canvas with C

Save drawing with S

Quit program with Q

Requirements

Python 3.x

OpenCV (opencv-python)

Numpy (numpy)

Install dependencies:

pip install opencv-python numpy

How to Use

Run the Python script:

python air_drawing.py


Hold a bright blue object in front of the camera.

Move it to draw.

Use the keys:

C → Clear canvas

S → Save drawing as PNG

Q → Quit the program

Tips:

Use bright blue objects for better detection

Good lighting improves tracking

Move slowly for smooth lines

Screenshots

Drawing Only shows your artwork

Blue Detection shows the mask for the blue object

Blue Air Drawing shows the blended output

License

This project is open-source.

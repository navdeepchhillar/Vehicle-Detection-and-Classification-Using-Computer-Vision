Heyy!!

Vehicle Detection and Counting Using YOLOv5 and OpenCV.

This project performs real-time vehicle detection, tracking, and counting in specific polygonal regions of a video using a custom-trained YOLOv5 model, OpenCV, and object tracking techniques.

Features :-
    
    - Detects vehicles (car, bus, truck) using a custom YOLOv5m model.    
    - Counts vehicles only within user-defined polygonal regions.
    - Avoids over-counting by assigning unique IDs to vehicles.    
    - Visualizes detection confidence across frames.    
    - Saves processed video with bounding boxes, labels, and counts.

First you have to install important dependencies :-

    - pip install opencv-contrib-python
    - pip install numpy
    - pip install torch
    - pip install matplotlib
    - pip install filterpy

Now open your git bash and :- 

    git clone https://github.com/abewley/sort.git

Folder Content :-

    .
    ├── coordinates.ipynb         # GUI to select custom polygon regions on video frame
    ├── video.ipynb               # Main script to detect, track, and count vehicles
    ├── yolov5m.pt                # Custom-trained YOLOv5 model weights
    ├── sort.py                   # SORT tracker script (if used)
    ├── 56310-479197605.mp4       # Input video
    ├── output.mp4                # Output video with annotations
    └── README.md

Itinerary :-

    1. Update directory in codes and install all necessary dependencies
    2. Run coordinates.ipynb, select polygon and copy all the coordinates.
    3. Paste coordinates in video.ipynb and run the code.
    4. After a little output video would be stored to the registered directory

That's it!!

### Hand-Controlled Desktop Mouse

This project transforms your hand movements into a mouse cursor, allowing you to control your desktop with gestures. It uses a webcam to detect and track hand landmarks in real-time.

-----

#### Features

  * **Cursor Movement**: Move your hand to move the cursor on the screen.
  * **Scrolling**: Scroll up and down by raising and lowering specific fingers.
  * **Zooming**: Zoom in and out by changing the distance between your index and middle fingers.
  * **Clicking**:
      * **Left Click**: Bring your index finger and thumb together.
      * **Right Click**: Bring your middle finger and thumb together.
      * **Double Click**: Bring your ring finger and thumb together.
  * **Dragging**: Make a fist to click and hold, enabling drag-and-drop actions.

#### Prerequisites

Before you can run the program, you need to install the necessary libraries. You can do this by running the following command in your terminal:

```bash
pip install -r requirements.txt
```

This will install:

  * `opencv-python`: For webcam access and image processing.
  * `mediapipe`: The core library for hand landmark detection.
  * `pyautogui`: To control your mouse and keyboard.

#### How to Run

1.  Clone this repository to your local machine.
2.  Install the prerequisites as described above.
3.  Run the main script from your terminal:
    ```bash
    python main.py
    ```

A window will open displaying your webcam feed. As you move your hand, you'll see the cursor on your screen react in real time.

-----

I've crafted a professional `README.md` file for your GitHub project, complete with a clear overview, a list of features, and simple instructions for setup and running the code.

What other sections or details would you like to add to the `README` file, such as a "Future Enhancements" section or a "Troubleshooting" guide?

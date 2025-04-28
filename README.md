
Gesture Controlled Virtual Mouse simplifies human-computer interaction using Hand Gestures and Voice Commands. No physical contact is needed — all I/O operations can be virtually controlled through gestures and voice.
The project uses Machine Learning and Computer Vision techniques, combining MediaPipe Hand Detection with pybind11 for real-time gesture recognition, along with a custom Voice Assistant (Proton).
Works smoothly without any external hardware and is optimized for Windows platform.

Note: Use Python version: 3.8.5

## Features

### Gesture Recognition:
- Move Cursor
- Left Click / Right Click / Double Click
- Scrolling
- Drag and Drop
- Volume Control
- Brightness Control
- Multiple Item Selection

### Voice Assistant (Proton):
- Launch/Stop Gesture Recognition
- Google Search
- Google Maps Location
- File Navigation (Open files/folders)
- Date and Time Query
- Copy and Paste Operations
- Sleep / Wake Up Proton
- Exit Command

## Getting Started

### Pre-requisites:
- Python 3.6 - 3.8.5
- Anaconda Distribution (Download [here](https://www.anaconda.com/products/individual))

### Setup Procedure:

```bash
git clone https://github.com/yourusername/Virtual-Mouse-Using-Hand-Gestures-AI-Mouse-Controller.git

2. **Step 1: Create a Conda environment:**

   ```bash
   conda create --name proton python=3.8.5
   ```

3. **Step 2: Activate the environment:**

   ```bash
   conda activate proton
   ```

4. **Step 3: Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Step 4: Install additional packages:**

   ```bash
   conda install pyaudio
   conda install pywin32
   ```

6. **Step 5: Navigate to the project’s `src` folder:**

   ```bash
   cd path_to_project/src
   ```

Just replace `yourusername` with your actual GitHub username, and your users will be able to clone your repository correctly.
```

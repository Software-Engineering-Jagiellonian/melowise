# Melowise

## Overview

This is a Music Ear Training App built for Android using Python and the Kivy framework. This application aims to help musicians, both amateur and professional, to develop a better musical ear for recognizing pitches, intervals, and chords.

## Features

- Recognize single pitches
- Identify different intervals
- Chord recognition
- Practice mode and Quiz mode
- Stat tracking

## Prerequisites

- Python 3.x
- Kivy
- Buildozer (for Android packaging)

## Installation

### Running on Desktop

1. Clone the repository
    ```
    git clone https://github.com/Software-Engineering-Jagiellonian/melowise.git
    ```
2. Change into the directory
    ```
    cd melowise
    ```
3. Install the requirements
    ```
    pip install -r requirements.txt
    ```
4. Run the app
    ```
    python main.py
    ```

### Running on Android

1. Install Buildozer
    ```
    pip install buildozer
    ```
2. Create the APK
    ```
    buildozer android debug
    ```
3. Install the APK on your Android device

## Usage

- **Single Pitch Recognition**: You will hear a pitch and have to identify it.
- **Interval Recognition**: You will hear two pitches and have to identify the interval.
- **Chord Recognition**: You will hear a chord and have to identify its quality (Major, Minor, Diminished, etc.)
- **Practice Mode**: Freely practice any of the above skills.
- **Quiz Mode**: Get scored on your ability to recognize pitches, intervals, or chords.

## Contribution

Feel free to fork the project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the GNU 3.0 License - see the [LICENSE](LICENSE) file for details.

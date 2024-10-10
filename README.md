# PaperPlaneVoiceInputPackage
# Paper Plane 3D Game

Paper Plane 3D is a Unity-based game where a paper plane moves forward endlessly. The objective is to keep the plane from falling by blowing air into the microphone. The plane only rises when the player blows air into the mic, simulating the sensation of flying.

## Gameplay

- The paper plane automatically moves forward.
- The plane falls by default due to gravity.
- Players need to blow air into their device's microphone to make the plane rise and avoid obstacles or falling to the ground.
- The game utilizes microphone input to detect air-blowing sounds, making it an interactive and immersive experience.

## Features

- **Endless Runner**: The paper plane flies along an infinite road.
- **Air Blowing Detection**: Microphone input detects air-blowing sounds and moves the plane up.
- **Smooth Controls**: The plane’s movement is smoothed to make the game feel more fluid and responsive.



## Screenshot

![Screenshot 2024-10-10 054132](https://github.com/user-attachments/assets/44ffe374-95e9-4666-97e5-57af94b2b403)
![Screenshot 2024-10-10 054204](https://github.com/user-attachments/assets/5f479753-41be-4914-bec9-f525088c0d93)


## Requirements

- **Unity**: Version 2019.4 or later is recommended.
- **Microphone Access**: The game requires microphone access to detect air-blowing sounds.

## Known Issues

- Microphone input may behave differently on various devices. Test and adjust the `micSensitivity` and `noiseThreshold` values accordingly in the code.


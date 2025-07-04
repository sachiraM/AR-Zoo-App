# 🦁 AR Zoo App

**AR Zoo** is a marker-based Augmented Reality (AR) application designed for an interactive zoo experience. This educational app brings five wild animals to life using AR technology, combining realistic 3D animations with natural sound effects.

## 📱 Features

- 🦓 **Five Animals**: Zebra, Lion, Camel, Hyena, and Sheep.
- 🎯 **Marker-Based AR**: Each animal appears when its unique image marker is scanned.
- 🎞️ **3D Animations**: Every animal is animated to mimic natural movement.
- 🔊 **Natural Sounds**: When an animal model appears, its real vocalization plays (e.g., lion roar, sheep bleat)
- ⚙️ **Built With**:
  - Unity Engine (Game engine for AR development)
  - Vuforia Engine (Image recognition & AR tracking)

## 🧠 How It Works

1. Open the AR Zoo app on your mobile device.
2. Scan one or more of the five image markers simultaneously to display multiple 3D animal models.
3. The corresponding 3D animal model will appear on the marker.
4. The model will animate and play the natural sound of that animal.

| Animal   | Marker Image                                                                             |
| -------- | ---------------------------------------------------------------------------------------- |
| 🦁 Lion  | [View Marker](https://github.com/sachiraM/AR-Zoo-App/blob/main/Screenshots/lion.PNG)  |
| 🐪 Camel | [View Marker](https://github.com/sachiraM/AR-Zoo-App/blob/main/Screenshots/camel.JPG) |
| 🐑 Sheep | [View Marker](https://github.com/sachiraM/AR-Zoo-App/blob/main/Screenshots/sheep.JPG) |
| 🦓 Zebra | [View Marker](https://github.com/sachiraM/AR-Zoo-App/blob/main/Screenshots/zebra.JPG) |
| 🐕 Hyena | [View Marker](https://github.com/sachiraM/AR-Zoo-App/blob/main/Screenshots/hyena.JPG) |

<h2>🚀 Getting Started</h2>

- Clone the repository.
- Install Git LFS and pull required files:
  ```bash
  git lfs install
  git lfs pull

  //If it fails, you can manually download the Vuforia `.tgz` package and place it inside the `Packages/` folder.
- Open the project in **Unity 6.1 (6000.1.3f1)** or newer.
- Make sure Vuforia is enabled.
- Go to Project Settings > XR Settings and enable Vuforia Augmented Reality.
- Open the appropriate scene: **Go to the Scenes folder and open the main scene file**
- Import the .tgz Vuforia package if not already present.
- Build and run the project on a mobile device.

<h3>📝 Notes</h3>

- Make sure your device camera permissions are enabled.
- Multiple image targets are supported.
- Git LFS is used to manage large files like the Vuforia .tgz package.

<h3>📷 ScreenShots</h3>

![Demo](Screenshots/screenshot5.JPEG)

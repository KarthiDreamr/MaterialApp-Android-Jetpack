# MaterialApp-Android-Jetpack 🎉📱

Welcome to the repository for the MaterialApp Android application built using Jetpack Compose! This app is a simple Material Design application that demonstrates the use of various Material Design components in Jetpack Compose. It's a fun and interactive way to explore the capabilities of Jetpack Compose. 😄🚀

## Features 🎯

### 1. MainActivity
- Inherits from `ComponentActivity`, which is a lean and modern `Activity` class designed for use with Jetpack Compose.
- In the `onCreate` method, it sets the content to a `Exercise1Theme` which contains a `Surface` that fills the maximum size of the screen. The `Surface`'s color is set to the background color of the current `MaterialTheme`.
- Inside the `Surface`, it calls the `Greeting` composable function.

### 2. Greeting Composable
- This is a composable function that displays a `Column` with a `Text` and a `Button`.
- The `Text` displays the current tap count.
- The `Button`, when clicked, increments the tap count and shows a `Toast` with the current tap count.
- The `Column` fills the maximum size of the screen and centers its children both horizontally and vertically.

### 3. GreetingPreview Composable
- This is a preview composable function that previews the `Greeting` composable.
- It wraps the `Greeting` composable with the `Exercise1Theme`.

## Screenshots 📸

*Coming soon...*

## How to run 🏃‍♂️

- Clone this repository using `git clone https://github.com/KarthiDreamr/MaterialApp-Android-Jetpack.git`
- Open the project in Android Studio Arctic Fox or later
- Run the app on an emulator or a physical device

## License 📝

This project is licensed under the GNU General Public License (GPL-3.0). The GPL is a strong copyleft license that requires improvements to be shared back with the community. For more information, see the [LICENSE](LICENSE) file.

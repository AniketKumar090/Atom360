# Atom360

A SwiftUI-based iOS camera application that demonstrates the implementation of SimpleCameraLibrary, providing an intuitive interface for capturing, reviewing, and managing photos.

## Features

- SwiftUI camera interface with capture button
- Real-time camera preview with overlay
- Post-capture review system
- Quick accept/reject functionality for captured photos
- Seamless photo management (save/delete)

## Requirements

- iOS 14.0+
- Xcode 13.0+
- Swift 5.0+
- SwiftUI 2.0+

## Installation

### Swift Package Manager

1. In Xcode, select File > Swift Packages > Add Package Dependency
2. Add the repository URL: `https://github.com/AniketKumar090/SimpleCameraLibrary.git`

## Usage

1. Import the required libraries in your SwiftUI view:
```swift
import SwiftUI
import SimpleCameraLibrary
```

2. Use the CameraView in your SwiftUI view:
```swift
struct ContentView: View {
    var body: some View {
        CameraView()
    }
}
```

## Demo

Below is a demonstration of the Atom360 app in action:

[View Demo Video](https://github.com/user-attachments/assets/491e3162-8af7-4f98-aa55-de1d5cf53343)

## Features Demonstrated in Video

- SwiftUI camera implementation
- Photo capture functionality
- Review overlay with accept/reject options
- Photo management workflow
- Library integration

## SimpleCameraLibrary Integration

This application serves as a demonstration of the SimpleCameraLibrary package, showcasing its core features and implementation patterns. The library provides a SwiftUI-compatible camera interface that can be easily integrated into other iOS applications.

## Permissions

The application requires the following permissions:
- Camera access
- Photo library access (for saving photos)

Add the following keys to your Info.plist:
```xml
<key>Privacy - Camera Usage Descriptionn</key>
<string>Atom360 needs camera access to take photos</string>
<keyPrivacy - Photo Library Usage Description</key>
<string>Atom360 needs photo library access to save photos</string>
```

## Contributing

1. Fork the repository
2. Create your feature branch 
3. Commit your changes 
4. Push to the branch
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

- Built as part of the iOS Developer Intern application process for Atom360
- Utilizes SimpleCameraLibrary for core camera functionality

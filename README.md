# MAD Practical 8: Hello World iOS App using SwiftUI

## 📌 Aim

To create a basic **Hello World iOS application using SwiftUI** in Xcode.

## 🛠️ Technologies Used

* **IDE:** Xcode
* **Programming Language:** Swift
* **UI Framework:** SwiftUI
* **Platform:** iOS
* **Execution Environment:** iOS Simulator

## 📖 Description

This practical demonstrates how to create and run a basic iOS application using SwiftUI. It introduces the structure of a SwiftUI project, the `App` protocol, the `ContentView` structure, and the process of previewing and running an application using the iOS Simulator.

The application displays the message **"Hello, world!"** on the screen.

## ⚙️ Steps to Perform

1. Open Xcode and select **File → New → Project**.
2. Select the **App** template under the iOS category.
3. Enter `hello_world` as the project name.
4. Select **SwiftUI** as the interface and **Swift** as the programming language.
5. Leave Core Data and unit testing options unselected.
6. Create the project and open `hello_worldApp.swift`.
7. Open `ContentView.swift` and verify the default SwiftUI code.
8. Select an iOS Simulator device.
9. Click the **Run (▶)** button to build and execute the application.
10. Verify that the application displays "Hello, world!".

## 💻 Source Code

### 1. hello_worldApp.swift

```swift
import SwiftUI

@main
struct hello_worldApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
```

**Explanation:**

* `import SwiftUI`: Imports the SwiftUI framework.
* `@main`: Specifies the entry point of the application.
* `App`: Defines the main structure of the application.
* `WindowGroup`: Creates a scene that manages the app's window.
* `ContentView()`: Displays the main user interface.

### 2. ContentView.swift

```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        Text("Hello, world!")
            .padding()
    }
}
```

**Explanation:**

* `ContentView`: Defines the main view of the application.
* `View`: A protocol used to create the user interface.
* `Text("Hello, world!")`: Displays the text on the screen.
* `.padding()`: Adds space around the text.

## ▶️ How to Run

1. Open the project in Xcode on a Mac.
2. Select an available iOS Simulator.
3. Press **Command + R** or click the Run button.
4. Wait for the build to complete.
5. Observe the Hello World application in the simulator.

## 🎯 Expected Output

The iOS Simulator displays a screen containing:

**Hello, world!**

The application should build and run successfully without errors.

## 📚 Concepts Learned

* Creating an iOS application in Xcode.
* Understanding the basic structure of a SwiftUI project.
* Using the `App` and `View` protocols.
* Displaying text using the `Text` view.
* Understanding `WindowGroup`.
* Running an application in the iOS Simulator.
* Previewing the user interface in Xcode.

## ✅ Result

Successfully created and executed a basic **Hello World iOS application using SwiftUI** in Xcode.

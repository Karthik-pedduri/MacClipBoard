# MacClipBoard

📝 **Description**  
MacClipBoard is a lightweight clipboard history utility designed to bring the convenience of the Windows clipboard manager to macOS. It provides a simple, native experience for accessing a history of all the text and images you copy. Never lose a copied item again and boost your productivity with this essential tool.

✨ **Features**  
- **Windows-Like Experience**: Designed to mimic the familiar and efficient workflow of the Windows clipboard history.  
- **Clipboard History**: Automatically saves a history of all text and images copied to your clipboard.  
- **Quick Access**: Easily browse and select past clipboard items from a convenient menu bar icon or a global shortcut.  
- **Search Functionality**: Quickly find a specific item from your history with a built-in search bar.  
- **Direct Paste**: Paste selected history items directly into your active application with a single click.  
- **Native & Lightweight**: Built with Swift and SwiftUI for a seamless, high-performance macOS experience.

📸 **Screenshots**  
* **Clipboard History Panel (Light Mode)**:  
    ![Clipboard History Panel](https://raw.githubusercontent.com/Karthik-pedduri/MacClipBoard/main/screenshots/light%20mode.png)  
    _A screenshot showing the quick access panel with recent clipboard items in light mode._  

* **Settings Window (Dark Mode)**:  
    ![Settings Window](https://raw.githubusercontent.com/Karthik-pedduri/MacClipBoard/main/screenshots/dark%20mode.png)  
    _A screenshot demonstrating the settings window where users can configure preferences in dark mode._

🚀 **Installation**  
The pre-built application is fully functional and ready for immediate use. You can download it directly and start boosting your productivity!

**Download Pre-built Application**  
You can download the latest pre-built `.app` file from the [Releases page](https://github.com/Karthik-pedduri/MacClipBoard/releases).

**Building from Source**  
To build and run MacClipBoard from its source code, you'll need Xcode installed on your macOS machine.

1. Clone the repository:
   ```bash
   git clone https://github.com/Karthik-pedduri/MacClipBoard.git
   cd MacClipBoard
   ```
2. Open in Xcode:  
   Open the `MacClipBoard.xcodeproj` file in Xcode.

3. Build and Run:  
   Select your target (e.g., "MacClipBoard") and click the "Run" button (▶️) in Xcode. The application will compile and launch.

💡 **Usage**  
- **Launch the Application**: After launching, MacClipBoard will appear as a clipboard icon in your macOS menu bar.  
- **Copy Content**: Simply copy any text or image as you normally would (`Cmd + C`). MacClipBoard will automatically add it to your history.  
- **Access History**:  
  - Click the clipboard icon in the menu bar.  
  - Use the global shortcut (`Cmd + Option + V` by default).  
- **Paste from History**: In the history panel, click on any item to automatically paste it into your currently active application.  
- **Settings**: Access settings from the menu bar icon to customize the maximum number of history items and change the global shortcut.

🔒 **Security & Privacy**  
MacClipBoard is designed with your privacy in mind.  
- **Completely Local**: All clipboard history data is stored only on your local machine. It is never transmitted to any external servers or third parties.  
- **No Data Collection**: The application does not collect any personal data or usage analytics.  
- **Open Source**: The source code is available for review, allowing you to verify its security and privacy practices.

**Important: Accessibility Permissions**  
MacClipBoard requires Accessibility Permissions to function correctly (to monitor clipboard changes and simulate paste actions). This permission is necessary for the app to interact with your system's clipboard and simulate keyboard presses for pasting.

Upon first launch, you may be prompted to grant these permissions. If not, or if you need to manually enable them:  
1. Go to **System Settings** (or **System Preferences**) > **Privacy & Security** > **Accessibility**.  
2. Find **MacClipBoard** in the list and enable the checkbox next to it.  
3. If **MacClipBoard** is not listed, you might need to drag the application from your Applications folder into this list.

🤝 **Contributing**  
Contributions are welcome! If you have suggestions for improvements or new features, please feel free to:  
1. Fork the repository.  
2. Create a new branch (`git checkout -b feature/YourFeature`).  
3. Make your changes and commit them (`git commit -m 'Add new feature'`).  
4. Push to the branch (`git push origin feature/YourFeature`).  
5. Open a Pull Request.  

Please ensure your code adheres to Swift style guidelines and includes appropriate tests.
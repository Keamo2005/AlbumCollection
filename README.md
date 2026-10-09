# Album Collection
- **Developer**: Keamo Seloane
- **Student Number**: ST10528238
- **Group**: 3
- **Course**: Higher Certificate in Mobile Application and Web Development
- **Subject**: MAST

## Links
- **GitHub Repository**: https://github.com/Keamo2005/AlbumCollection

---

## Project Overview

The **Album Collection** is a app developed as part of an assignment in the MAST subject. This application was created using **Kotlin** and **Visual Studio**. The app's primary purpose is a album collection.

The **Album Collection** application is a mobile utility built using React Native, Expo, and TypeScript designed to help users track and organize their favorite music albums. The application features a comprehensive entry form that captures key details such as Album Title, Artist Name, Release Year, Genre (a dropdown picker), and a personal Rating out of 5 stars.

## Development Environment

The application was debugged, optimized, and tested using the following software stack and configurations:
- Expo
- React Native
- TypeScript
- Institutional VM (Virtual Machine Environment)
-  BlueStacks 5 (Android Development Virtualization)
-  Expo Go

---

## Error Log

Below is the breakdown of the syntax issues, component bugs, and logic errors discovered in the original codebase, along with explaining what was wrong and how it was corrected:

- Changed import to <expo/ui/community> 
- 
- 
---

## GitHub and GitHub Actions

This project was managed using **GitHub** for version control, where all code changes were committed and pushed regularly. GitHub enabled collaborative coding, allowing me to keep track of changes and maintain project integrity.

### GitHub Actions:
I utilized **GitHub Actions** to automate the build and deployment process. This includes:

- Running automated **tests** to ensure the appâ€™s functionality.
- Compiling the app into **APK** and **AAB** files, which are the formats required for distribution.
- Uploading these build artifacts to GitHub for easy access.

The workflow ensures that my project is automatically built and tested every time I push changes, and it simplifies the process of delivering the final APK/AAB files for submission.

---

## 4. Testing

The corrected application bundle was evaluated inside the BlueStacks 5 emulator runtime via the Expo Go application:

* **Multi-City Testing:** Interactively clicked through the Johannesburg, Cape Town, and Durban selector buttons. Confirmed that active tabs updated theme colors cleanly and that the global dashboard successfully swapped data matrices without memory stalls.
* **Swipe Testing:** Mouse-drag swipe interactions across the 24-Hour Forecast array.

* **Error** Emojis are cropped out.
---

### App Screenshot:

<img width="540" height="960" alt="Screenshot_2026 10 09_15 08 04 642" src="https://github.com/user-attachments/assets/3f255fdd-e295-430b-9446-d1afdb4644ff" />


---

## 6. Conclusion
Investigating and refactoring the broken Weather Dashboard code provided key insights into the layout constraints of React Native text rendering, type structures, and framework component states. 
Resolving the terminal crashes emphasized that React Native enforces a strict validation rule: no text strings or stray characters may exist outside a `<Text>` component container boundary. Furthermore, adjusting the 5-Day Forecast loop maps clarified the syntax difference between component returns using parentheses `()` versus statement blocks using curly braces `{}`. 
Ultimately, this task demonstrated the importance of development terminal logs to isolate syntax issues and implement target style buffers when deploying applications to mobile emulators.

---

## References

Jessel Sookha - Album Collection coding

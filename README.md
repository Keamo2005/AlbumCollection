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
- Used `&&` operator| Logic Error | Updated to use the logical `||` operator.
- Missing maximum validation checking variables| Logic Error | Implemented `numericYear > currentYear` and `numericRating > MAX_RATING` .
- Entries overwrote active memory collections | Runtime State | Modified methods to use array spread notation (`[...currentAlbums, temporaryAlbum]`).
- Deleting entries used (`===`) | Logic Error | Inverted the equality condition to  (`album.id !== id`). 
- Picker assigned `selectedValue` | Data-Binding | Set `selectedValue={genre}` to use `value={item}`. 
- FlatList  values (`item.title`) | Performance | Reconfigured list to unique structural lookups `item.id`.

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

The application underwent systematic confirmation checking according to the 5 mandatory assessment blocks:

- **Initial Launch** The application successfully loaded into the Expo Go environment on the BlueStacks emulator. The startup process was completely clean, generating zero configuration warnings or setup errors.
- **Valid Album Creation** Submitting a fully completed form passed all data verification checks. The system successfully created the new album entry and immediately cleared the active text fields so the form was ready for the next input.
- **Managing Multiple Albums** The application handles complex state changes correctly by using proper state spreads. This allows multiple independent album cards to display simultaneously in clean rows without any layout collisions or mixed-up data.
- **Deletion Functionality** The delete feature safely removes data from the user interface. Clicking the delete element on a specific card instantly removed that entry from the screen while keeping all neighboring cards completely intact.

---

### App Screenshot:

<img width="540" height="960" alt="Screenshot_2026 10 09_15 08 04 642" src="https://github.com/user-attachments/assets/3f255fdd-e295-430b-9446-d1afdb4644ff" />


---

## 6. Conclusion

This debugging task provided practical experience in tracing updates and identifying type mismatches within React Native and TypeScript. 
Resolving logical check bounds highlighted the importance of boundary constraints, while fixing state mutations reinforced how React handles memory reference tracking to update user interfaces.
Additionally, navigating management commands inside an institutional VM environment provided valuable experience in deploying cross-platform apps to production-grade mobile emulators.

---

## References

Jessel Sookha - Album Collection coding

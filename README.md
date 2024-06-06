# Android Project: Internationalization with Kotlin

## Overview

This is a simple Android project developed in Kotlin that explores the feature of internationalization (i18n). Internationalization allows the application to support multiple languages, providing a better experience for users from different regions and languages.

## Features

- Support for multiple languages (e.g., English and Portuguese)
- Dynamic language switching based on the device's system settings
- Utilization of localized string resources

## Environment Setup

To set up the development environment, follow these steps:

1. **Install Android Studio**: Make sure you have Android Studio installed. You can download it [here](https://developer.android.com/studio).

2. **Clone the Repository**: Clone this repository to your local machine.
   ```bash
   git clone https://github.com/guilhermefelype/My-first-DIO-Android-App
   ```

3. **Open the Project**: Open Android Studio and select "Open an existing Android Studio project". Navigate to the cloned directory and open it.

4. **Sync the Project**: Sync the project with Gradle to download all necessary dependencies.

## Adding Support for a New Language

To add support for a new language:

1. **Create a New Resource Directory**: In the `res` directory, create a new folder named `values-<language-code>` (e.g., `values-es` for Spanish).

2. **Add Localized Strings**: Inside the new directory, add a `strings.xml` file and translate the strings as needed.

   ```xml
   <!-- res/values-es/strings.xml -->
   <resources>
       <string name="app_name">MyFirstDIOAndroidApp</string>
   </resources>
   ```

3. **Test the New Language**: Change the system language of your device or emulator to verify the translation.

## Resources

- [Android Internationalization Documentation](https://developer.android.com/guide/topics/resources/localization)
- [Kotlin for Android Developers](https://developer.android.com/kotlin)

## Contributions

Contributions are welcome! To contribute, follow these steps:

1. Fork this repository.
2. Create a branch with your feature: `git checkout -b my-feature`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin my-feature`.
5. Open a Pull Request.


## Contact

If you have any questions or suggestions, feel free to open an issue or contact us.

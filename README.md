
# Cross Browser Testing for Facebook

This repository contains automated test scripts for performing cross-browser testing of Facebook functionality using Selenium WebDriver. The tests cover login, registration, profile editing, and post creation across multiple browsers (Chrome, Edge, and Firefox).

## Features

- **Cross-Browser Testing**: Validate Facebook functionality on Chrome, Edge, and Firefox.
- **Test Scenarios**:
  - Login functionality testing.
  - Registration page validation and form submission.
  - Profile information editing.
  - Post creation and verification.
- **Selenium WebDriver**: Used for browser automation.
- **Ease of Setup**: Easily configurable for multiple environments.

## Prerequisites

- Install Java Development Kit (JDK) 8 or higher.
- Install Maven for dependency management.
- Download the appropriate WebDriver executables for Chrome, Edge, and Firefox:
  - [ChromeDriver](https://chromedriver.chromium.org/downloads)
  - [EdgeDriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/)
  - [GeckoDriver (Firefox)](https://github.com/mozilla/geckodriver/releases)
- Ensure you have Selenium dependencies configured in your project.

## Directory Structure

```
.
├── src
│   └── demo11
│       └── UpdatedT.java
├── README.md
└── WebDrivers
    ├── chromedriver.exe
    ├── msedgedriver.exe
    └── geckodriver.exe
```

## Setup and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/cross-browser-testing-facebook.git
   ```

2. Navigate to the project directory:
   ```bash
   cd cross-browser-testing-facebook
   ```

3. Update WebDriver paths in `UpdatedT.java` with the locations of your WebDriver executables.

4. Compile and run the test script using your IDE or command line.

   **Command line (if using Maven):**
   ```bash
   mvn compile
   mvn exec:java -Dexec.mainClass="demo11.UpdatedT"
   ```

5. Test results will be displayed in the console.

## Author

- Aditya Sinha and Syed Ubaid
- GitHub: [Your GitHub Profile](https://github.com/AdityaSinha07)

## License

This project is licensed under the MIT License. See `LICENSE` for details.

---

**Note**: This project is for educational and testing purposes only. Use responsibly.

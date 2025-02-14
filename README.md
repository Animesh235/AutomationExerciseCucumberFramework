# AutomationExerciseCucumberFramework
## Folder Breakdown 📂
![code_20250214_182622_via_10015_io](https://github.com/user-attachments/assets/1478b173-3834-4c13-b82c-6d9a17d4b5cc)
### ✅ `src/main/java/com/yourcompany/`
- **`pages/`** → Contains Page Object Model (POM) classes for UI elements.
- **`utils/`** → Utility/helper functions (e.g., Excel reading, API calls).
- **`base/`** → Base test class for setup & teardown methods.
- **`constants/`** → Stores constants (URLs, timeouts).
- **`config/`** → Manages configurations like environment settings.

### ✅ `src/main/resources/`
- **`config.properties`** → Stores global configurations (URL, username, password).
- **`testdata/`** → External test data (CSV, JSON, XML, Excel).
- **`drivers/`** → Chrome, Firefox, Edge WebDriver executables.

### ✅ `src/test/java/com/yourcompany/`
- **`stepdefinitions/`** → Implements Gherkin steps from `.feature` files.
- **`runners/`** → Test runner classes (JUnit/TestNG for Cucumber).
- **`hooks/`** → Hooks (Before, After) for setup & teardown.
- **`tests/`** → Organizes test execution logic.

### ✅ `src/test/resources/features/`
- Contains `.feature` files with Gherkin syntax (Given, When, Then).
- Organized per module (Login, Search, Checkout).

### ✅ `src/test/resources/reports/`
- Stores Cucumber, Extent, or Allure reports.

### ✅ `screenshots/`
- Saves screenshots of test failures for debugging.

## Extra Configuration Files
- **`pom.xml`** → Manages dependencies (Cucumber, Selenium, TestNG, JUnit).

---

## Getting Started 🚀

### Prerequisites
Ensure you have the following installed:
- Java (JDK 8 or later)
- Maven
- IDE (IntelliJ IDEA, Eclipse, or VS Code)
- WebDriver executables (ChromeDriver, GeckoDriver, etc.)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourcompany/cucumber-automation.git
   ```
2. Navigate to the project directory:
   ```sh
   cd cucumber-automation
   ```
3. Install dependencies:
   ```sh
   mvn clean install
   ```

### Running Tests
- To execute tests, run:
  ```sh
  mvn test
  ```
- To generate reports:
  ```sh
  mvn verify
  ```

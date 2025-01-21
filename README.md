# Weather App Development Project in 3 Days

## Objective
Create a simple weather application using Xcode, Swift, and SwiftUI. By the end of this project, you will have a fully functional app displaying weather information fetched from the OpenWeather API.

---

## Day 1: UI Development (Mock-Up Design)
### Goal
Build the UI for the weather app based on the provided mock-up.

![Screenshot #1](./screenshot%20#1.png)
![Screenshot #2](./screenshot%20#2.png)

### Tasks
1. **Set Up the Project:**
   - Open Xcode and create a new SwiftUI project named `WeatherApp`.
   - Organize your project folders: `Views`, `Models`, and `Services`.

2. **Build the Main Screen:**
   - Use SwiftUI to create a UI that replicates the mock-up.
   - Include the following components:
     - **Header:** Display location, temperature, and weather conditions.
     - **Hourly Forecast Section:** Horizontal scrollable view showing hourly temperature and icons.
     - **10-Day Forecast Section:** List view displaying daily weather details with min/max temperatures.

3. **Styling:**
   - Use `ZStack` for the background image.
   - Use appropriate system colors and fonts to mimic the mock-up design.

### Deliverables
- A static UI for the main screen with mock data.
- Screenshots of the completed UI.
- Updated code in the GitHub repository.

---

## Day 2: Architecture & Modularization
### Goal
Organize your app’s codebase and prepare for data integration.

### Tasks
1. **Design the Architecture:**
   - Follow MVVM (Model-View-ViewModel) architecture.
   - Create separate files and modules for the following:
     - **Views:** UI components.
     - **ViewModels:** Handle business logic and data processing.
     - **Models:** Define data structures (e.g., `WeatherData`).
     - **Services:** Handle API calls and networking.

2. **Prepare for API Integration:**
   - Define a `WeatherService` protocol for API-related methods (e.g., `fetchWeatherData`).
   - Implement a mock data provider to simulate API responses.

3. **Connect UI with ViewModel:**
   - Use `@StateObject` or `@ObservedObject` to bind your ViewModel to the UI.
   - Update the UI to display mock data from the ViewModel.

### Deliverables
- Modularized codebase with well-organized folders.
- Screenshots or videos showing the UI updating based on mock data.
- Updated code in the GitHub repository.

---

## Day 3: API Integration & Finalization
### Goal
Integrate the OpenWeather API to fetch real-time weather data and finalize the app.

### Tasks
1. **Set Up API Integration:**
   - Sign up for an API key from [OpenWeather API](https://openweathermap.org/api).
   - Add the API key to your project securely (e.g., use `Info.plist` or environment variables).
   - Implement the `WeatherService` class to fetch data using `URLSession`.

2. **Update ViewModel:**
   - Use the `WeatherService` class to fetch real data.
   - Parse the API response and update the UI with real weather information.

3. **Error Handling:**
   - Display error messages for API failures (e.g., network issues).

4. **Enhancements:**
   - Add animations or transitions for UI updates.
   - Optimize performance for smooth scrolling and data loading.

### Deliverables
- A fully functional weather app displaying real-time data.
- Video demo showcasing the app.
- Updated code in the GitHub repository.

---

## Evaluation Criteria
1. **Completion of Tasks:**
   - UI matches the mock-up.
   - Functional integration of OpenWeather API.
2. **Code Quality:**
   - Follows MVVM architecture.
   - Well-structured and commented code.
3. **Creativity:**
   - Additional features or UI improvements beyond the requirements.

Good luck and have fun building your weather app!

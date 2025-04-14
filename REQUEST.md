## Project Title: Weatherly Application Assessment

### Overview
Welcome to our mobile development skills assessment! In this project, you'll build **Weatherly**, a weather application that allows users to:
- Search for cities and view their current weather conditions
- Save favorite cities for quick access
- View detailed weather information for selected locations

---

### Core Technical Requirements

#### 1. User Interface Design
**Goal**: Create a platform-appropriate UI that follows design best practices.

**For iOS Developers:**
- Develop a main view with search functionality and favorites list
- Create a detailed weather view for selected cities
- Implement using UIKit or SwiftUI with iOS design principles
- Incorporate Material Design elements where appropriate

**For Android Developers:**
- Build a main screen with search and favorites functionality
- Design a city details screen showing weather data
- Utilize Material Design components (Bottom Navigation, Cards, FAB)

**Evaluation Points:**
- Platform design guideline adherence
- Overall UX and visual appeal
- Code organization and clarity

---

#### 2. Weather Data Integration
**Goal**: Connect to a weather API and present data to users.

**Supported APIs:**
- OpenWeatherMap: https://openweathermap.org/api
- Weatherbit: https://www.weatherbit.io/api
- Weatherstack: https://weatherstack.com/documentation
- Open-Meteo: https://open-meteo.com/en/docs

**For iOS Developers:**
- Implement network requests using URLSession or Alamofire
- Parse JSON responses with Codable or SwiftyJSON
- Display formatted weather data in the detail view

**For Android Developers:**
- Use Retrofit, Volley, or Ktor for API communication
- Parse JSON with Gson or Moshi
- Present weather information in the detail screen

**Evaluation Points:**
- Network request implementation
- Data parsing accuracy
- UI integration of weather data

---

#### 3. Local Data Management with Realm
**Goal**: Implement persistent storage for favorite cities.

**For iOS Developers:**
- Configure Realm database
- Create city model objects
- Implement complete CRUD operations
- Demonstrate proper querying for favorites

**For Android Developers:**
- Set up Realm instance
- Define appropriate Realm objects
- Build CRUD functionality
- Show efficient querying techniques

**Evaluation Points:**
- Database configuration
- CRUD operation correctness
- Query efficiency

---

### Additional Requirements

#### Code Quality
- Follow language and platform-specific best practices
- Use consistent naming conventions
- Include appropriate documentation

#### Testing
- Include at least one unit or integration test

#### Performance
- Implement efficient data loading
- Consider memory management best practices

---

### Submission Guidelines
1. Push project to a Git repository
2. Include a comprehensive README with:
   - Setup instructions
   - API usage notes
   - Any additional implementation details
3. Share repository link for review

Thank you for participating in our assessment. We look forward to reviewing your work!

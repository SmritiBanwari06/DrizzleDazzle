# DrizzleDazzle

 
DrizzleDazzle, a single-page weather forecast application developed with ReactJS, is designed to provide users with a seamless experience in accessing current weather details and a 5-day forecast for a selected city. The project utilizes the popular create-react-app to establish a well-organized folder structure, including components, services, and styles. The application incorporates a user-friendly interface with components such as SearchForm for city input, CurrentWeather for displaying real-time weather details, and ForecastList for showcasing the 5-day forecast. To enhance the user experience, the application is designed to be responsive across different devices, employing CSS or styled-components for styling. The integration with a public weather API, such as OpenWeatherMap, is handled through a dedicated service in the src/services folder. The React state management system, leveraging useState and useEffect hooks, ensures efficient handling of state and side effects. Additionally, robust error handling is implemented to provide clear messages in case of invalid city names or other issues. With a focus on maintainability and adherence to best practices, DrizzleDazzle aims to offer an intuitive solution for users seeking weather information.


To run the DrizzleDazzle project locally:

Clone the repository: git clone <repository-url>
Navigate to the project: cd drizzle-dazzle
Install dependencies: npm install
Obtain an API key (e.g., from OpenWeatherMap).
Create a .env file with your API key: REACT_APP_API_KEY=your_openweathermap_api_key
Run the application: npm start
Open http://localhost:3000 in your browser.

Netlify Link: https://drizzledazzle.netlify.app/

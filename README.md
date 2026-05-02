# GenLayer API Toolkit Starter
export async function getWeather(city) {
  return `Weather data for ${city}`;
}
Starter toolkit for enabling Intelligent Contracts to interact with external APIs securely.
export function secureRequest(apiKey) {
  return "Request sent securely";
}
## Features
- Weather API adapter
- Secure request middleware
- Example contract integration
import { getWeather } from "../adapters/weatherAdapter.js";

console.log(getWeather("London"));
## Structure
- adapters/
- middleware/
- examples/

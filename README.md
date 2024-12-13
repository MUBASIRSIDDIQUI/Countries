
# Mubasir Siddiqui Country Submission

## Project Overview
A simple iOS application that demonstrates login functionality and displays a list of countries with their flags.

## Features
- Secure login screen with username and password authentication
- Countries list retrieved from an external API
- Support for displaying both PNG and SVG flag images
- Clean, programmatic UI design using UIKit

## Screenshots
*Screenshots would be added here in an actual project*

## Prerequisites
- Xcode 15 or later
- iOS 15+
- Swift 5.5+

## Dependencies
This project uses the following third-party libraries:
- Alamofire (Networking)
- Kingfisher (Image Loading)
- SVGKit (SVG Image Rendering)

## Installation
1. Clone the repository
2. Open the project in Xcode
3. Run `pod install` to install dependencies
4. Build and run the project

## Architecture
- MVVM-inspired architecture
- Programmatic UI using UIKit
- No storyboard dependencies for core functionality

## Login Credentials
- **Username**: Admin
- **Password**: password

## API
Countries data is fetched from: https://countriesnow.space/api/v0.1/countries/flag/images

## Key Components
- `LoginViewController`: Handles user authentication
- `CountriesVC`: Displays the list of countries with their flags
- `CountryResponse` and `Country`: Data models for API response

## Error Handling
- Basic error alerts for login failures
- Placeholder images for flag loading failures

## Potential Improvements
- Implement more robust authentication
- Add search and filter functionality to country list
- Implement persistent login state
- Add unit and UI tests

## Author
Mubasir Siddiqui

## License
*Add your license information here*

## Acknowledgments
- Alamofire
- Kingfisher
- SVGKit

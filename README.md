# Hotel Management Application

## Overview
The Hotel Management Application is designed to facilitate the management of hotel operations, including room management and guest check-in/check-out processes. This application provides a user-friendly interface for hotel staff to efficiently manage their daily tasks.

## Project Structure
```
hotel-management-app
├── src
│   ├── main.cpp          # Entry point of the application
│   ├── hotel.cpp         # Implementation of the Hotel class
│   ├── hotel.h           # Definition of the Hotel class
│   ├── room.cpp          # Implementation of the Room class
│   ├── room.h            # Definition of the Room class
│   ├── guest.cpp         # Implementation of the Guest class
│   ├── guest.h           # Definition of the Guest class
│   ├── utils.cpp         # Utility functions implementation
│   └── utils.h           # Utility functions declaration
├── CMakeLists.txt        # CMake configuration file
└── README.md             # Project documentation
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   cd hotel-management-app
   ```

2. Create a build directory and navigate into it:
   ```
   mkdir build
   cd build
   ```

3. Run CMake to configure the project:
   ```
   cmake ..
   ```

4. Build the project:
   ```
   make
   ```

## Usage
- Run the application:
  ```
  ./hotel-management-app
  ```

- Follow the on-screen instructions to manage hotel operations, including checking in and checking out guests, and managing room availability.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
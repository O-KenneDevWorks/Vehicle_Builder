# Vehicle Builder
 
## Description
Vehicle Builder is a command-line interface (CLI) application built in TypeScript that allows users to create, manage, and interact with different types of vehicles, including cars, trucks, and motorbikes. The application enables users to perform various actions such as starting the vehicle, accelerating, and performing unique actions based on the vehicle type.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Known Issues](#known-issues--future-development)
- [How to Contribute](#how-to-contribute)
- [License](#license)
- [Questions](#questions)

## Features

- Create New Vehicle: Users can create a new vehicle by providing details such as vehicle type, color, make, model, year, weight, and more.

- Select Existing Vehicle: Users can select an existing vehicle from a list of previously created vehicles.

- Perform Actions: Users can perform actions such as starting the vehicle, accelerating, reversing, and performing special actions based on the vehicle type (e.g., towing for trucks).

- Class Inheritance: The application uses object-oriented principles, including inheritance and method overriding for vehicle-specific behaviors (e.g., Trucks and Motorbikes).

- Dynamic Prompts: The application uses the Inquirer package to interactively guide the user through the vehicle creation and action selection process.

## Installation
1. Clone the repository:
```
git clone https://github.com/yourusername/vehicle-builder.git
```

2. Navigate to the project directory:
```

cd vehicle-builder
```

3. Install dependencies:
```
npm install
```

4. Build the TypeScript code:
```
npm run build
```

5. Run the application:
```
npm start
```

## Usage
Once the application is running, users will be prompted with several options:

1. Create or Use an Existing Vehicle: Choose between creating a new vehicle or performing actions on an existing vehicle.
    - If creating a new vehicle, select the type (Car, Truck, Motorbike) and enter the required details.
    - If selecting an existing vehicle, choose from a list of previously created vehicles.
2. Perform Actions: Once a vehicle is selected or created, you can:
    - Start the vehicle
    - Accelerate by a specified amount
    - Stop the vehicle
    - Print the vehicle details
    - Perform vehicle-specific actions (e.g., Towing for Trucks or Wheelie for Motorbikes)

[Video Example](https://drive.google.com/file/d/1uhljFLVijivjKsbKC8EUFjCtYxkaUgXz/view?usp=sharing)

### Example Run
```
$ npm start

> vehicle-builder@1.0.0 start
> npm run build && node dist/index.js

? Would you like to create a new vehicle or perform an action on an existing vehicle? (Use arrow keys)
  > Create a new vehicle
    Select an existing vehicle

? Select a vehicle type (Use arrow keys)
  > Car
    Truck
    Motorbike

? Enter the vehicle color: Blue
? Enter the vehicle make: Toyota
? Enter the vehicle model: Camry
? Enter the vehicle year: 2021
? Enter the vehicle weight (lbs): 3000
? Enter the vehicle top speed (mph): 130

Vehicle created successfully!

? Select an action (Use arrow keys)
  > Start vehicle
    Print details
    Accelerate
    Stop vehicle
    Reverse
    Turn left
    Turn right
```

## Known Issues & Future Development
- The application is designed for a single user session. Closing the CLI will lose all vehicle data.
- Further enhancements can include data persistence using a database or file system to retain vehicle information across sessions.

## How to Contribute
If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. For any major changes, open an issue first to discuss what you'd like to change.

1. Fork the Project
2. Create your Feature Branch (```git checkout -b feature/AmazingFeature```)
3. Commit your Changes (```git commit -m 'Add some AmazingFeature'```)
4. Push to the Branch (```git push origin feature/AmazingFeature```)
5. Open a Pull Request

## License
This project is licensed under the MIT License.

## Questions
For any inquiries or issues, please contact:

- Name: Owen Kenne
- Email: <okenne.devworks@gmail.com>
- GitHub: [O-KenneDevWorks](https://github.com/O-KenneDevWorks)

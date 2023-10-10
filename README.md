# Termux PHP Banner

This is a simple script that creates a dynamic banner in PHP to display on your Termux terminal. The banner can be customized with different colors, text, and ASCII art.

## Table of Contents
- Requirements
- Installation
- Usage
- Customization
- Contributing
- License

## Requirements
- Android device with Termux installed
- Internet connection

## Installation
1. Clone or download this repository to your local machine.
2. Transfer the termux-php-banner.php file to your Android device using methods like ADB or file transfer apps.
3. Open Termux and navigate to the directory where you transferred the termux-php-banner.php file.
4. Install PHP by running the following command:
      pkg install php
   
5. Grant permission to run PHP script by executing:
      chmod +x termux-php-banner.php
   

## Usage
To run the PHP banner, simply execute the following command in your Termux terminal:
php termux-php-banner.php

The banner will be displayed with the default settings.

To stop the banner, press Ctrl + C.

## Customization
You can customize the banner by modifying the variables in the script according to your preferences. Open the termux-php-banner.php file in a text editor and change the values of the variables below:

- $text: Set this variable to the desired text you want to display in the banner.
- $textColor: Set this variable to the desired color for the text. You can use ANSI color codes or predefined variables like "black", "red", "green", etc.
- $backgroundColor: Set this variable to the desired color for the background. You can use ANSI color codes or predefined variables like "black", "red", "green", etc.
- $asciiArt: Set this variable to the desired ASCII art or comment it out with // if you don't want any ASCII art.

Save the changes and follow the Installation and Usage steps to see your customized banner in action.

## Contributing
Contributions are welcome! If you would like to enhance the features, fix any bugs, or add improvements to this project, please feel free to fork this repository and submit a pull request.

## License
This project is licensed under the MIT License.
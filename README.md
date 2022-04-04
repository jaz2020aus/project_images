# Bus stop customer satisfaction

Bus stop is a Python program created to take input from a bus driver to enter a route number, how many stops along the route, how many passengers get on and off at each stop without exceeding the capacity of the bus (47 passengers) and to return the results reguarding happy customers (people who could get on the bus) vs unhappy customers (people who missed the bus due to capacity limits) in a ratio with 2 decimal places.

## Installation
To install this program you will need to first remove it from the .tgz file. I have included a .GIF to show you how to do this as well as written instructions. Please open your terminal window and follow the steps below.

    Step 1. Type: cd ~/ # press enter key (ensure you are in the home directory)

    Step 2. Type: ls # press enter key(to confirm that pt1.tgz file exists if not contact support)

    Step 3. Type: mkdir busstop # press enter key (create a folder to store the program in)

    Step 4. Type: mv pt1.tgz ~/busstop/ # press enter key (moves the file pt1.tgz to the busstop directory)

    Step 5. Type: cd ~/busstop # press enter key (change to the busstop directory)

    Step 6. Type: tar -zxf pt1.tgz # press enter key (extract files to current directory (~/busstop))

    step 7. Type: ls # press enter key ( you should now show 3 files busstop.py, README.md and pt1.tgz. If files missing go back to step 1)

    Step 8. Type: ./busstop.py # press enter key ( to start the program, if the program doesn't start ensure all steps were followed, if it still wont start please contact support)

![If you can't see this .gif please follow the above steps](.gif)

**Requirements**\
[Python](https://www.python.org/) program running on any supported OS environment including [Windows](https://www.microsoft.com/en-au/windows), [MacOS](https://www.apple.com/au/macos/monterey/), [Linux](https://www.linux.org/).

## Run program
After following the steps under installation heading.\
Type the following into the terminal command prompt to start the program.

```python
./busstop.py
```

## Usage

```python
#/usr/bin/env python3

# Get route number of bus stop ensuring that only a number is entered.
 route = input ("Please enter route number: ") 15  # correct input type

# Get number of stops along route number must be greater than 2 stops.
stops = input ("\nPlease enter the number of stops on this route: ") 5 # correct input type

# Get number of passengers waiting at each stop only 47 passengers can be on the bus at any time
# any more than 47 those still waiting will be counted as unhappy customers.
get_on = input ("\nHow many passengers were waiting for the bus at stop#" + str(stopnum) + "?.") 30 # correct input type

# Get number of passengers getting off the bus, cannot exceed the passengers currently on the bus.
get_off = input ("\nHow many passengers get off at bus stop #" + str(stopnum) + "?.") 15 #correct input tpye

```
## Support
For support please use this email address for any enquiries regarding any issues or problems with the code <jphill44@myune.edu.au>

## Contributing
Open to any and all contributions, please ensure that adequate testing has been done on any modifications and add details to support section of README file.

## Author
Program created by Jai phillipps-lewis march 2022.

## License
[MIT](https://choosealicense.com/licenses/mit/)
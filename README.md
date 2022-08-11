# 0x00.AiBnB Clone - The Console
The console is the first segment of the AirBnB project at Holberton School that will collectively cover fundamental concepts of higher level programming. The goal of AirBnB project is to eventually deploy our server a simple copy of the AirBnB Website(HBnB). A command interpreter is created in this segment to manage objects for the AirBnB(HBnB) website.
## _Functionalities of this command interpreter:_

 - Create a new object (ex: a new User or a new Place)
 - Retrieve an object from a file, a database etc...
 - Do operations on objects (count, compute stats, etc...)
 - Update attributes of an object
 - Destroy an object

## _Environment_
This project is interpreted/tested on Ubuntu 14.04 LTS using python3 (version 3.4.3)

## _Instalation_
 - Clone this repository: git clone "https://github.com/Elias-Tesfu/AirBnB_clone.git"
 - Access AirBnB directory: cd AirBnB_clone
 - Run hbnb(interactively): ./console and enter command
 - Run hbnb(non-interactively): echo "" | ./console.py

## _File Description_
This team project is part of alx Software Engineer program. It's the first step towards building a first full web application: an AirBnB clone. This first step consists of a custom command-line interface for data management,and the base classes for the storage of this data.
| File | Description | Attributes |
| ------ | ------ | ------ |
| base_model.py | The Base Model class is inherited by other | id, created_at, updated_at |
| user.py | User class stores user-related info | email, passoword, first_name, last_name |
| city.py | City class stores city-specific info | state_id, name |
| state.py | State class stores state-specific info | name |
| place.py | Place class stores full detailed outline of rental unit | city_id, user_id, name, descirption, number_rooms, number_bathrooms, max_guest, place_by_night, latitude, longitude, amenity_ids |
| review.py | stores pervious customer reviews | place_id, user_id, text |
| amenity.py | Stores highlighted amenity info | name |

## _Console & Command Usage_
The console is a Unix shell-like command line user interface provided by the python CmdModule It prints a prompt and waits for the user for input, for our project we used (hbnb)
| Command | Example |
| ------ | ------|
| Display commands help | (hbnb) help |
| Create Object (prints its ID) | (hbnb) create |
| Destroy Object | (hbnb) destroy or (hbnb) .destroy() |
| Show Object | (hbnb) show or (hbnb) .show() |
| Show "all" objects or instance class | (hbnb) all |
| Run console | ./console.py |
| Quit console | (hbnb)quit |

#### _Usage Example_
(hbnb) help

## _Bugs_
No known bugs at this time.

## _Authors_
Elias Tesfu - [Elias](https://github.com/Elias-Tesfu)

## Philosophy
MVC pattern
- Model
- View
- Controller

Ignition pattern
- View
- Interface
- Service
### Services
Services are functionalities of the system and use all the neccesary resources as modules, crates, python-scripts, third APIs, system, etc.
### Crates
Crates are binary programs that should be managed by the stdout and stdin
### Interfaces
Interfaces are the communication handlers between view/interface and services

### Constraints
- Views only can communicate with Interfaces and not itselves
- Views cannot manipulate the data of the user input
- All the view logic should be managed by an interface
- Crates are accessible only by a service
- The master object(all the user data related to a topic) should be managed by the view itself
- Interface will validate the data from views
- Interface will handler data errors and manipulate the view as necessary and warn user inputs. A popup message should report the error
- Interface should manage broken data
- Views that contains hot-reload data may be managed by a reload button

### Benefits
- New capabilities
- Easy scalability
- Same logic for all views
- Avoid security problems from views
- Standard development
- Faster and easy debugging
- Easy error managing


## Perspective views

views should use flex

TODO research about flex position elements and best strategy

TODO check strategy about global variables and how to queue data reading and insertion

TODO check about an strategy to organize the views

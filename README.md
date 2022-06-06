# Library Management System
REST API for library management system built with Express, MongoDB and Pug.

## Organization

### The main entities/resources served by the API are
- Books
- Authors
- Book Instances
- Genres

### Each resource structured in 4 modules
- Router
- Model
- Controller
- View

## Accessing the API 
### Book routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /                                  | Public  | View home page                           |
| GET     | /book/:id/create                   | Public  | Get form to add a book                   |
| POST    | /book/:id/create                   | Public  | Create a book                            |
| GET     | /book/:id/delete                   | Public  | Get form to delete a book                |
| POST    | /book/:id/delete                   | Public  | Delete a book                            |
| GET     | /book/:id/update                   | Public  | Get form to update a book                |
| POST    | /book/:id/update                   | Public  | Update a book                            |
| GET     | /book/:id                          | Public  | View a book                              |
| GET     | /books                             | Public  | View list of all books                   |

### Author routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /author/:id/create                 | Public  | View all tasks                           |
| POST    | /author/:id/create                 | Public  | View a task                              |
| GET     | /author/:id/delete                 | Public  | Update a task                            |
| POST    | /author/:id/delete                 | Public  | Delete a task                            |
| GET     | /author/:id/update                 | Public  | View all tasks                           |
| POST    | /author/:id/update                 | Public  | Create a task                            |
| GET     | /author/:id                        | Public  | View a task                              |
| GET     | /authors                           | Public  | Update a task                            |

### Genre routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /genre/:id/create                  | Public  | View all tasks                           |
| POST    | /genre/:id/create                  | Public  | View a task                              |
| GET     | /genre/:id/delete                  | Public  | Update a task                            |
| POST    | /genre/:id/delete                  | Public  | Delete a task                            |
| GET     | /genre/:id/update                  | Public  | View all tasks                           |
| POST    | /genre/:id/update                  | Public  | Create a task                            |
| GET     | /genre/:id                         | Public  | View a task                              |
| GET     | /genres                            | Public  | Update a task                            |

### Book Instance routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /bookinstance/:id/create           | Public  | View all tasks                           |
| POST    | /bookinstance/:id/create           | Public  | View a task                              |
| GET     | /bookinstance/:id/delete           | Public  | Update a task                            |
| POST    | /bookinstance/:id/delete           | Public  | Delete a task                            |
| GET     | /bookinstance/:id/update           | Public  | View all tasks                           |
| POST    | /bookinstance/:id/update           | Public  | Create a task                            |
| GET     | /bookinstance/:id                  | Public  | View a task                              |
| GET     | /bookinstances                     | Public  | Update a task                            |



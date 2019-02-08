# Component Hierarchy

**AuthFormContainer**
* AuthForm

**NavBar**
* SearchBar
* Links

**Home**
* NavBar
* Pins

**UserPage**
* NavBar
* UserStats
* UserBoards
* UserPins

**SearchResultPage**
* NavBar
* UsersStats


# Routes

| **Path**  | **Component** |
| ------------- | ------------- |
| '/'  | 'Homepage'  |
| '/sign-up'  | 'AuthFormContainer'  |
| '/sign-in'  | 'AuthFormContainer'  |
| '/users'  | 'UserIndex'  |
| '/users/:userId'  | 'UserPage'  |

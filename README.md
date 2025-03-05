# Team and Player List SwiftUI App

This SwiftUI app displays a list of teams and players, using an Object-Oriented Programming (OOP) approach for data modeling. It utilizes a `Player` struct and a `Team` class, while an enum categorizes the teams into National, Club, or Academy types. The app uses an `ObservableObject` ViewModel to manage the data and dynamically update the UI with `@Published`.

## Features
- Displays a list of teams, each with its own players.
- Teams are categorized as National, Club, or Academy using an enum.
- Real-time UI updates through a `ViewModel` with `@Published` properties.

## Data Model
- **Player**: A struct representing a player with attributes like name and position.
- **Team**: A class representing a team with a list of players and a type (National, Club, or Academy).
- **TeamType**: An enum categorizing teams into National, Club, or Academy.

## ViewModel
- The `TeamViewModel` is an `ObservableObject` that holds a list of teams.
- It includes methods to add teams and players, and dynamically updates the UI.

## Conclusion
This app demonstrates a SwiftUI implementation with OOP principles for managing teams and players. It leverages state management with `ObservableObject` to provide dynamic UI updates.

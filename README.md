RickAndMortyApp-iOS
Project Description

Welcome to the repository of the "Rick and Morty" iOS app! Our goal is to provide fans with an immersive experience, exploring detailed information about characters, episodes, and locations from the animated series "Rick and Morty." The app utilizes the public API of "The Rick and Morty" to fetch updated and relevant data.
Key Features

    Character Exploration: Get detailed information about your favorite characters, including their origin, species, and status.

    Episodes: Explore the complete list of episodes with details such as names, numbers, and air dates.

    Locations: Discover fascinating places visited by Rick and Morty during their intergalactic adventures.

Architecture and Design Patterns

This project adheres to Clean Architecture, organizing into independent layers for clean, maintainable, and testable code. Additionally, it implements the Coordinator and MVVM design patterns to enhance code modularity and scalability.
Clean Architecture

    Presentation Layer (UI): Implements the MVVM design pattern to separate presentation logic from business logic.

    Domain Layer: Contains business rules and core logic independent of concrete implementation.

    Data Layer: Manages data retrieval and storage, connecting to "The Rick and Morty" API.

    Root Composition Module: Utilizes the root composition module to structure and assemble all project components.

Design Patterns

    Coordinator: Used for handling navigation between modules and presenting screens in an organized manner.

    MVVM (Model-View-ViewModel): Facilitates a clear separation between presentation logic and business logic, improving code testability and maintainability.

Development Requirements

    Xcode 12.0 or higher
    Swift 5.0
    Internet connection to access "The Rick and Morty" API

Installation

    Clone this repository to your local machine.
    Open the project in Xcode.
    Ensure an active internet connection for the application to fetch data from the API.

We hope you enjoy exploring the "Rick and Morty" multiverse with our iOS app!

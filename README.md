# Music Management System
## Overview
The Music Management System is a Java-based application that manages artists, songs, and copyrights. It provides a graphical user interface for users to interact with the system, allowing them to add, edit, and delete records.

## Features
* Manage artists, including adding, editing, and deleting artist records
* Manage songs, including adding, editing, and deleting song records
* Manage copyrights, including adding, editing, and deleting copyright records
* Display scrolling text animations and other visual effects

## Architecture
The system consists of three main components: Controller, Model, and View. The Controller handles user input and events, the Model manages data and business logic, and the View renders the graphical user interface. The system uses a directory structure with separate packages for artists, copyrights, and songs. The Composite design pattern is used in the InitialPanelArtists class.

## Getting Started

### Prerequisites
* Java Development Kit (JDK)
* Java Runtime Environment (JRE)

### Installation
```bash
# Clone the repository
git clone https://github.com/username/repo_name.git
# Change into the repository directory
cd repo_name
```

### Configuration
No specific configuration is required.

### Usage
```bash
# Compile the Java code
javac *.java
# Run the application
java Main
```

## Development

### Project Structure
```
repo_path
|-- Controller.java
|-- Model
|   |-- Model.java
|   |-- Artists
|   |   |-- Artists.java
|   |   |-- Celebrities.java
|   |   |-- EmailException.java
|   |   |-- FileHandlingArtists.java
|   |   |-- ManageArtists.java
|   |-- Copyrights
|   |   |-- Copyrights.java
|   |   |-- FileHandlingCopyrights.java
|   |   |-- ManageCopyrights.java
|   |-- Songs
|   |   |-- FileHandlingSongs.java
|   |   |-- ManageSongs.java
|   |   |-- MediaItems.java
|   |   |-- RatingException.java
|   |   |-- Songs.java
|-- Utils
|   |-- Displayable.java
|-- View
|   |-- FirstFrame.java
|   |-- ScrollText.java
|   |-- CreditsFrame.java
|   |-- Main.java
```

### Core Components
The main components of the system are the Controller, Model, and View. The Controller handles user input and events, the Model manages data and business logic, and the View renders the graphical user interface.

### Building
```bash
# Compile the Java code
javac *.java
```

### Testing
No test commands are available.

## Contributing
Contributors should follow standard Java coding conventions and submit pull requests with clear descriptions of changes.

## License
No license information is available.
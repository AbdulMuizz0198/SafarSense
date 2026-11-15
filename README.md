# SafarSense

## Smart Travel Planning and Destination Discovery System

SafarSense is a C++ application that helps users plan trips and explore
destinations. Users can enter their travel plans or describe the kind of
trip they want. The application uses available destination and travel
information to provide suggestions and help users compare their options.

## Main Features

### Plan a Trip

-   Enter a destination, travel date and trip duration.
-   View available information about the selected destination.
-   Get travel and packing suggestions.
-   Save a trip for later.

### Discover Destinations

-   Enter preferences such as region and temperature range.
-   Find destinations that match those preferences.
-   View suggested destinations and their matching scores.

### Compare Destinations

-   Select two or more destinations.
-   Compare their available information.
-   See which destination best matches the user's preferences.

### Weather Information

-   View available weather information for selected destinations and
    dates.
-   Check temperatures and expected conditions when forecast data is
    available.
-   Get suggestions based on the information provided.

### Saved Trips and Favourites

-   Save and view planned trips.
-   Delete trips that are no longer needed.
-   Add destinations to a favourites list.

### Travel Information

-   View general information about destinations.
-   Display available travel alerts and road updates.
-   Find useful information before travelling.

## Technologies

-   C++
-   Visual Studio Code
-   GCC or MinGW compiler
-   Text files for data storage
-   Git and GitHub
-   Weather API and JSON library (planned)

## Project Structure

``` text
SafarSense/
|
|-- main.cpp
|
|-- destination.h
|-- destination.cpp
|
|-- trip.h
|-- trip.cpp
|
|-- weather.h
|-- weather.cpp
|
|-- recommendation.h
|-- recommendation.cpp
|
|-- fileHandling.h
|-- fileHandling.cpp
|
|-- Data/
|   |-- destinations.txt
|   |-- savedTrips.txt
|   |-- favourites.txt
|
|-- README.md
```

## File Details

  -----------------------------------------------------------------------
  File                                Purpose
  ----------------------------------- -----------------------------------
  `main.cpp`                          Starts the application and displays
                                      the main menu.

  `destination.h` and                 Store and manage destination
  `destination.cpp`                   information.

  `trip.h` and `trip.cpp`             Create and manage trips.

  `weather.h` and `weather.cpp`       Retrieve and process weather
                                      information.

  `recommendation.h` and              Find and rank destinations based on
  `recommendation.cpp`                user preferences.

  `fileHandling.h` and                Read and write application data.
  `fileHandling.cpp`                  

  `destinations.txt`                  Stores destination records.

  `savedTrips.txt`                    Stores saved trips.

  `favourites.txt`                    Stores favourite destinations.
  -----------------------------------------------------------------------

## C++ Concepts

The project will use the following concepts:

-   Variables and data types
-   Conditional statements and switch
-   Loops
-   One-dimensional and multidimensional arrays
-   Functions
-   Structures
-   Strings
-   Pointers and references
-   Pass by value and pass by reference
-   Functions with arrays and pointers
-   File handling
-   Recursion, if it is useful for a project feature

## How to Compile

Open a terminal in the project folder and run:

``` bash
g++ main.cpp destination.cpp trip.cpp weather.cpp recommendation.cpp fileHandling.cpp -o SafarSense
```

On Windows, run:

``` bash
SafarSense.exe
```

On Linux, run:

``` bash
./SafarSense
```

A C++ compiler is required. Weather API access and any required external
libraries will need to be configured when those features are added.

## Data Storage

The application will use text files to keep information between runs.

-   `destinations.txt` contains destination details.
-   `savedTrips.txt` contains saved trip records.
-   `favourites.txt` contains favourite destinations.

## Possible Future Additions

-   Trip budget estimates
-   Accommodation suggestions
-   Transportation information
-   Multi-day itineraries
-   More detailed destination recommendations
-   A graphical user interface

## Project Information

**Course:** CS-101\
**Project:** SafarSense\
**Language:** C++\
**Project type:** Semester programming project

### Team Members

1.  Member 1
2.  Member 2
3.  Member 3

------------------------------------------------------------------------

SafarSense: Make every journey a smarter journey.

# NYC Subway Route Finder (Java)

A beginner-friendly Java project that helps users find which NYC subway trains connect two stations.  
Inspired by everyday commuting in NYC and built as a simple introduction to maps, lists, and route-search algorithms.

## Purpose

NYC has one of the largest subway systems in the world, and figuring out which trains connect two stations can be confusing—especially for someone new to the city.  

This project simulates a basic version of an MTA-style route finder:

- You enter a **start station**
- You enter an **end station**
- The program tells you which trains stop at *both* stations  
- If no direct route exists, it suggests using a major transfer station


## Skills & Concepts Used

This project is designed to show early CS skills clearly and professionally:

- `HashMap<String, List<String>>`
- Lists & Arrays
- Loops
- Conditionals
- Input with `Scanner`
- Basic search logic
- Organized and readable Java code

Great for internships, research applications, and GitHub portfolios.


## How to Run

To run the Subway Route Finder on your computer:

  Make sure you have **Java installed** (Java 8 or higher).  
   Check by running:
   ```bash
   java -version
   javac SubwayRouteFinder.java
   java SubwayRouteFinder

## Example Output
🚇 NYC Subway Route Finder
---------------------------------
Enter your START station: 59 St
Enter your END station: 42 St

---------------------------------
🔍 Searching for routes...
---------------------------------

✅ You can take the following direct train(s): [A, 1, F, 6]

Thanks for using the Subway Route Finder!

# tree_frog_movie_database

# Project Overview

This project designs a movie database with about 40 sample records per table.
Tree Frog Movie Database is a centralized movie information system that stores and connects data about films, actors, directors, writers, awards, genres, ratings, and soundtracks. The database helps audiences, critics, producers, and casting directors quickly find and analyze movie-related information, such as actor biographies, filmographies, awards, and reviews. By organizing information in a relational database, the system improves searchability, reduces data redundancy, and makes it easier to discover relationships within the film industry.

# Project Purpose

This database helps people who work in the movie industry and anyone interested in movies, look up related information.
The purpose of the Tree Frog Movie Database is to provide a centralized, relational database that stores and organizes information about movies, actors, directors, producers, writers, awards, genres, ratings, soundtracks, and audience feedback. The system is designed to help audiences, critics, casting directors, and producers efficiently search, analyze, and discover connections within the film industry. By reducing data redundancy and improving access to interconnected information, the database supports informed decision-making, media research, talent discovery, and enhanced audience engagement.

## Key Features of the Tree Frog Movie Database

- Movie Information Management: Store and manage detailed information about films, including title, release year, genre/category, ratings, awards, locations, trailers, and soundtracks.

- People and Biography Tracking: Maintain profiles for actors, directors, producers, and writers, including biographical details such as birth date, age, place of birth, and career information.

- Filmography Search: View all movies associated with a specific actor, director, producer, or writer.

- Awards Management: Track awards received by movies and individuals, including award type, year received, and associated film.

- Genre and Category Classification: Organize movies by genres such as Action, Comedy, Horror, Animated, Superhero, and other categories to support discovery and recommendation.

- Music and Soundtrack Information: Record and search soundtrack and music information linked to specific films.

- Ratings and Reviews: Allow critics and audience members to submit ratings and feedback to support movie evaluation and engagement.

- Advanced Search Capabilities: Search for films, actors, directors, writers, awards, genres, ratings, soundtracks, and related information through a centralized system.

- Industry Research and Talent Discovery: Support casting directors and producers by providing actor histories, biographies, headshots, reels, and writer credits.

- Relationship-Based Data Analysis: Connect movies, people, awards, genres, and ratings through relational database structures, making it easy to explore industry relationships and trends.

- Data Consistency and Reduced Redundancy: Store information once and reuse it across related records, reducing duplicate data and improving database accuracy.

- Decision Support: Provide data that can help users evaluate movie success factors, identify trends, and make informed casting, production, or viewing decisions.

# Database Design
EER included in repo

# How to Run the SQL Scripts
TBA - Provide clear instructions for setting up the database and executing your SQL files.

# Technologies Used

MySQL
MySQL Workbench
Microsoft Excel
GitHub
Database Features
macOS 26.2
Windows 11

# View movie ratings
Look up personal information about favorite actors and directors
Find the movies they appeared in and the awards they won
Find highly rated movies in the same genre
See which awards a movie has won
Database Design

# EER Diagram

One key design decision was the movie_credit table. One person can join a movie in more than one role. For example, Ben Affleck was the director, an actor, and a producer in Argo. If the primary key were only person_id and movie_id, his second and third roles would be duplicates and could not be saved. So the primary key includes person_id, movie_id, and role.

# Challenges
## Ning
My biggest challenge was deciding how tables should relate to each other, how many tables I needed, and how deep to go. While checking data, I also found two famous people named Steve McQueen, so I had to confirm which one was the director. To solve these problems, I followed the project handout, kept the design simple, and tested my tables by thinking through 1NF, 2NF, and 3NF. Sample data was organized with AI help and checked on Wikipedia; reviewers and ratings are fictional.

## Richard
The table design in draw.io was tedious. Additionally, the work must be repeated to create the schema SQL file. Looking back, I would have created the EER in Workbench, then used File > Export > 

## Miguel
TBD


# Project Structure
- README.md
- design/ Entity Relationship Diagrams (ERDs), database models, and other design-related files.
- docs/ Project requirements, written reports, documentation, and other supporting materials
- sql/ SQL scripts used to create tables, insert data, retrieve information, and implement database functionality. 


# Team Contributions
- Ning Peng
- Miguel Lasola
- Richard Lopez



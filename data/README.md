# Data Folder
[![ReadMe](https://img.shields.io/badge/ReadMe-018EF5?logo=readme&logoColor=fff)](#)

## Overview
The `data` folder contains all the necessary files required for the multi-agent system to function effectively. It includes user input files, configuration files, and other resources used by the agents during execution.

## File Structure
- **`cv.txt`**: A sample text file containing the profile information (e.g., CV or resume) that the system analyzes. This file is used as input by agents like the CV Analyser and Skills Extractor.
- **`courses.txt`**: A text file containing a list of available courses. This is utilized by the Courses Recommender agent to match candidate profiles with relevant courses.

## File Details
### `cv.txt`
- **Purpose**: Input file for the multi-agent system to analyze a user's profile.
- **Format**: Plain text (`.txt`) containing details such as name, experience, skills, and education.
- **Example Content**:
  ```plaintext
  Name: John Doe
  Experience: 5 years in software development
  Skills: Python, Java, SQL
  Education: BSc in Computer Science

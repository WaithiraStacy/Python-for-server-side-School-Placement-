Student Placement System

Overview

The Student Placement System is a Flask-based API designed to streamline high school placement for students. It evaluates candidate details, such as exam scores, gender, age, and special needs status, to determine appropriate school placements. Additionally, the system integrates with OpenStreetMap's Nominatim API to suggest nearby schools based on the candidate's location. This solution provides an efficient and automated way to process student placements, reducing manual efforts and ensuring fairness in the selection process.

Features

Accepts candidate details via a POST request.

Determines school placement based on predefined criteria.

Stores candidate information in a MySQL database.

Fetches nearby school locations based on the candidate's city.

Technologies Used

Python (Flask)

MySQL

OpenStreetMap (Nominatim API)

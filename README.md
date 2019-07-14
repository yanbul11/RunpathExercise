# RunpathExercise

Solution to Runpath Exercise.

The entry point is the WebAPI application "Exercise.Api", configured to run in IIS Express with base url "https://localhost:44379/".
The requirements mentioned in the exercise are supported by the following relative urls:

1. api/albums
2. api/albums/[userId]

Examples:

1. https://localhost:44379/api/albums
2. https://localhost:44379/api/albums/1

The exercise includes a unit test project (Exercise.Services.Test) which tests the requirements using as test data a part of the actual data (2 users, 4 albums and 8 photos).

# Basic prototype quiz

You're going to build prototype chains for movies.

1. Create a base Movie function
2. Create a base MovieGenre function
2. Create several functions for each genre you want to use (e.g. comedy, action, etc.).
3. Create several MovieTitles (e.g. function JoeDirt() {}; ) that have Movie as their prototype.
4. Create a setter function on the MovieTitle prototype for assigning a genre (e.g. `setGenre`)

The base Movie function should have default values for the following properties.

+ length (decimal number)
+ title (string)
+ actors (array)
+ release_year (number)
+ genre

The Genre function should have default values for the following properties.

+ genre (string)

The MovieTitle function is the one that you will be creating with the `new` keyword.

1. Create several MovieTitle objects.
2. Set the appropriate value for genre on each one of them through a setter function you added to the prototype. Use an instance of the corresponding Genre to set the genre.
3. Assign the appropriate value for each of the other properties when you create the MovieTitle.

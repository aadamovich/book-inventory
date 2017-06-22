
# book-inventory

Thsi repository contains script to generate labels for books in my personal library.

## Running

To generate book labels from the `books.list` file, run the following command:

    gradlew build 

If needed, adjust the `badge_template.svg` for different design. 

Currently the script is optimized to work with A4 pages which has 16 sticky labels with the following dimensions `105mmx33.8mm`:

![t](https://raw.githubusercontent.com/aadamovich/book-inventory/master/LABELS.png)

The result looks like this:

![t](https://raw.githubusercontent.com/aadamovich/book-inventory/master/PAGE.png)


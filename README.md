# FiveM Map Collision Finder

A tool designed to assist map developers and server owners with finding map collisions in their servers and projects. 

### Prerequisites

- Python 3.x

### Installation
   ```bash
   git clone https://github.com/puttydotexe/fivem-map-collision-finder.git
   ```

### Usage
   ```bash
   python checker.py <directory> [--ignore PATTERN [PATTERN ...]] [--output OUTPUT_FILE]
   ```

### Example Usage
   ```bash
   python checker.py /resources/[maps] --ignore *.ydd output.log
   ```
   > If an output file isn't provided, it will simply output the possible collisions in the command line.

### License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](LICENSE).

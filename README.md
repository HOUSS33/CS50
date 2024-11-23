
# Image Filter Project

## Description
This project implements image filtering features like grayscale, sepia, blur, and reflection for BMP images. Users can apply these filters via command-line arguments.

## Installation 
To compile the project, use the following command:
```bash
$ make filter
```

## Usage
Once the project is compiled, you can run the program with the following command(-g for grayscale, -s for sepia, -b for blur, -r for reflection):
```bash
$ ./filter [filter-option] input-file output-file
```
Exemple:
```bash
$ ./filter -g input.bmp out.bmp
```
images/yard.bmp:
This is the input file that contains the original image. The program reads this file to extract pixel data.

out.bmp:
This is the output file where the program saves the resulting image after applying the chosen filter. It will be created in the same directory where you run the command.

## Available Filters

- **Grayscale**: Converts the image to black and white.
- **Sepia**: Converts the image to a sepia tone.
- **Reflection**: Reflects the image horizontally.
- **Blur**: Applies a box blur to the image.

## Contributing
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request with a description of what you've changed.

## License
This project is licensed under the MIT License.


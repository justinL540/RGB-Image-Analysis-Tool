**This project identifies and names the most common color found in any .jpg image using image analysis and an external color API. The goal is to help users quickly find and visualize the dominant color in any image by name, hex code, and RGB values.**

**Functionality**
- Users run the script and input the filename of a .jpg image.
- The image must be saved in the same folder as the Python script.
- The script processes the image and outputs:
- The closest color name (via TheColorAPI)
- The matching RGB and hex values

**Tools & Libraries Used**
- PIL: Opens and processes image files
- collections.Counter: Counts RGB color frequencies
- requests: Sends API calls to TheColorAPI
- matplotlib: Visualizes color data with bar charts

**Visual Output**
- Chart 1: RGB breakdown (Red, Green, Blue bars)
- Chart 2: A solid bar filled with the most common color

**API Note**
- The project uses TheColorAPI to translate RGB values into real-world color names. If the exact color isn’t available, the closest match is returned.

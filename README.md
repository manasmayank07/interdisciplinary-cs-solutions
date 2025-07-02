# Interdisciplinary CS Solutions

Java solutions for selected programming exercises from **_Computer Science: An Interdisciplinary Approach_** — covering image processing and string manipulation.

## 📂 Contents

- **3.1.4 Histogram**  
  A program that takes the name of a grayscale image file as input and uses `StdDraw` to plot a histogram showing the frequency of each of the 256 grayscale intensity values.

- **3.1.22 Substrings**  
  A program that takes a start string and stop string and prints all substrings of a given text that:
  - start with the start string,
  - end with the stop string,
  - contain neither start nor stop in between,
  - and handles overlaps correctly.

## 🚀 How to Run

1. **Compile:**
   ```bash
   javac Histogram.java
   javac Substrings.java
java Histogram <image-file>
java Histogram gray_image.png
java Substrings <start> <stop>

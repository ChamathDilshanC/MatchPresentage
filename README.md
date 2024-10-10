# 🧮 Match Percentage Calculator

Welcome to the Match Percentage Calculator project! This tool calculates the percentage match between two strings, providing a simple yet effective way to compare text similarities.

## ✨ Features

- **String Comparison**: Calculate the similarity between two input strings.
- **Percentage Output**: Get a clear percentage value representing the match.
- **Case Insensitive**: Comparisons are case-insensitive for broader matching.
- **Whitespace Handling**: Properly handles whitespace in input strings.
- **User-Friendly Interface**: Simple command-line interface for easy use.

## 🛠️ Technologies Used

- Java
- [Any additional libraries or frameworks you've used]

## 🚀 Getting Started

To get this Match Percentage Calculator up and running on your local machine:

1. Clone the repository:
   ```sh
   git clone https://github.com/ChamathDilshanC/MatchPresentage.git
   ```
2. Navigate to the project directory:
   ```sh
   cd MatchPresentage
   ```
3. Compile the Java files:
   ```sh
   javac *.java
   ```
4. Run the main program:
   ```sh
   java Main
   ```

## 💻 Usage

When you run the program, you'll be prompted to:

1. Enter the first string
2. Enter the second string

The program will then calculate and display the percentage match between the two strings.

Example:
```
Enter the first string: Hello World
Enter the second string: hello world
Match Percentage: 100.0%
```

## 🧠 Algorithm

The match percentage is calculated using the following steps:
1. Convert both strings to lowercase to ensure case-insensitive comparison.
2. Remove any leading or trailing whitespace.
3. Calculate the Levenshtein distance between the two strings.
4. Use the formula: Match% = (1 - LevenshteinDistance / max(length1, length2)) * 100

## 📁 Project Structure

```
src/
├── Main.java
├── MatchCalculator.java
└── [Any other Java files in your project]
```

## 🤝 Contributing

Contributions are welcome and greatly appreciated! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Contact

Chamath Dilshan - dilshancolonne123@gmail.com

Project Link: [https://github.com/ChamathDilshanC/MatchPresentage](https://github.com/ChamathDilshanC/MatchPresentage)

---

⭐️ If you find this project helpful or interesting, please give it a star! ⭐️

# Character Dialogue in Public Domain Novels

This repository contains structured CSV datasets of character dialogue exchanges from four classic public domain novels. Each CSV includes all dialogue lines, along with information about the **speaker**, **receiver**, and the **chapter** where the dialogue occurs.

## 📚 Included Novels

The datasets cover the following novels, all sourced from [Project Gutenberg](https://www.gutenberg.org):

1. **A Study in Scarlet** by Arthur Conan Doyle  
2. **The Mysterious Affair at Styles** by Agatha Christie  
3. **The Stainless Steel Rat** by Harry Harrison  
4. **The Time Traders** by Andre Norton  

## 📂 Dataset Structure

Each CSV file is organised with the following columns:

- `chapter`: The chapter number where the dialogue occurs.  
- `dialogue`: The text of the dialogue line.  
- `speaker`: The character delivering the dialogue.  
- `receiver`: The character or group receiving the dialogue (if identifiable) -- sometimes one dialogue line is directed to multiple receivers, in which case it is repeated in the dataset to represent relationship strength.  

### Example Row
| chapter | dialogue                          | speaker         | receiver       |
|---------|-----------------------------------|-----------------|----------------|
| 1       | "You see, but you do not observe."| Sherlock Holmes | John Watson    |

## 🧑‍💻 Usage

These datasets are designed for researchers, developers, and enthusiasts interested in:

- Natural Language Processing (NLP)  
- Literary analysis  
- Character interaction modelling  
- Visualisations of dialogue networks  

Feel free to use this data in your projects or analyses. Attribution to this repository and Project Gutenberg is appreciated!

## 📜 Licensing

All novels included in this repository are in the public domain. The texts were sourced from [Project Gutenberg](https://www.gutenberg.org), a free resource for public domain texts.

The datasets and code in this repository are licensed under the [MIT License](LICENSE).

## 🙌 Contributions

Contributions, suggestions, and bug reports are welcome! If you notice any inconsistencies in the datasets or would like to add more novels, feel free to open an issue or submit a pull request.

## 🔗 Acknowledgements

- Texts sourced from [Project Gutenberg](https://www.gutenberg.org).  
- Datasets compiled by Natalie House (nvhouse).

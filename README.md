# Character Dialogue in Public Domain Novels

This repository contains structured CSV datasets of character dialogue exchanges from four classic public domain novels. Each CSV includes all dialogue lines, along with information about the **speaker**, **receiver**, and the **chapter** where the dialogue occurs. These datasets were manually annotated with every effort made to ensure accuracy. However, in some cases, the receiver was inferred based on contextual descriptions, which introduces a degree of subjectivity to certain annotations. The receiver field is left blank in instances where the text indicates that the speaker is either talking to themselves or speaking in a way that others cannot hear them. Additionally, some dialogue lines are directed to multiple receivers. In such cases, the line is repeated in the dataset for each receiver to accurately represent relationship strength.

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
- `receiver`: The character or group receiving the dialogue (if identifiable). 

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

## 🙌 Contributions

Contributions, suggestions, and bug reports are welcome! If you notice any inconsistencies in the datasets or would like to add more novels, feel free to open an issue or submit a pull request.

## 🔗 Acknowledgements

- Texts sourced from [Project Gutenberg](https://www.gutenberg.org).  
- Datasets compiled by Natalie House (nvhouse).

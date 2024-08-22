# Cyberbullying Detection using HateXplain Dataset

## About the Dataset
This dataset contains annotated social media comments specifically curated for the analysis and detection of cyberbullying. The data is labeled across multiple categories including race, religion, gender, sexual orientation, and miscellaneous attributes. Each comment has been carefully reviewed and annotated by multiple annotators to ensure accuracy and reliability.

### Original Dataset Format
The original dataset in HateXplain was provided in JSON format. Below is a sample entry:
json { "1179055004553900032twitter": { "postid": "1179055004553900032twitter", "annotators": [ {"label": "normal", "annotatorid": 1, "target": ["None"]}, {"label": "normal", "annotatorid": 2, "target": ["None"]}, {"label": "normal", "annotatorid": 3, "target": ["None"]} ], "rationales": [], "post_tokens": ["i", "dont", "think", "im", "getting", "my", "baby", "them", "white", "9", "he", "has", "two", "white", "j", "and", "nikes", "not", "even", "touched"] } }

### Processed Dataset
This dataset is a scraped and well-processed version of the above data, specially designed for metadata extraction.

#### hateXplain.csv
- **post_id:** Unique ID for each post
- **annotators:** The list of annotations from each annotator
  - **annotators[label]:** The label assigned by the annotator to this post. Possible values: [Hatespeech, Offensive, Normal]
  - **annotators[annotator_id]:** The unique ID assigned to each annotator
  - **annotators[target]:** A list of target communities present in the post
- **rationales:** A list of rationales selected by annotators. Each rationale represents a list with values 0 or 1. A value of 1 means that the token is part of the rationale selected by the annotator. To get the particular token, we can use the same index position in "post_tokens".
- **post_tokens:** The list of tokens representing the post which was annotated.

#### final_hateXplain.csv
Different label categories and their respective values:
- **Race:** no_race, african, arab, asian, caucasian, hispanic, indian, indigenous
- **Religion:** nonreligious, buddhism, christian, hindu, islam, jewish
- **Gender:** no_gender, men, women
- **Sexual Orientation:** no_orientation, asexual, bisexual, heterosexual, homosexual
- **Miscellaneous:** none, disability, economic, minority, other, refugee

## Acknowledgement
I would like to acknowledge the original work and the creators of the dataset:
bibtex @inproceedings{mathew2021hatexplain, title={HateXplain: A Benchmark Dataset for Explainable Hate Speech Detection}, author={Mathew, Binny and Saha, Punyajoy and Yimam, Seid Muhie and Biemann, Chris and Goyal, Pawan and Mukherjee, Animesh}, booktitle={Proceedings of the AAAI Conference on Artificial Intelligence}, volume={35}, number={17}, pages={14867--14875}, year={2021} }

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For inquiries, please contact [your email or GitHub profile link].
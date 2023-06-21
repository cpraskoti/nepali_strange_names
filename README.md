# Nepali Strange Names and Nicknames

![Funny Names](/images/logo.png) 

Welcome to the Strange Nepali Names Dataset repository! This project aims to collect and curate a dataset of peculiar, amusing, and rare names from around the world. Whether you've encountered a hilarious name in a book, stumbled upon an amusing moniker on social media, or heard of a unique name from a friend, this repository is the perfect place to contribute and share these gems.

## Motivation

The Strange and Funny Names Dataset project was initiated with the objective of celebrating the diversity and humor that exists in the realm of personal nomenclature. Naming conventions differ greatly across cultures and languages, and this repository serves as a lighthearted collection of such intriguing names. By assembling a comprehensive dataset of these unconventional names, we hope to provide a valuable resource for various purposes, such as creative writing, comedy, or simply indulging in a good laugh.

## Contribution Guidelines

We encourage and welcome contributions from anyone who encounters a name that fits the criteria of being strange, funny, or rare. To contribute to this repository, follow these simple steps:

1. Fork this repository to your GitHub account.
2. Clone the forked repository to your local machine.
3. In the `data` directory, add a new file named `<name>.json`, where `<name>` is the name you encountered (e.g., `John_Doe.json`).
4. Inside the JSON file, structure the data with the following fields:
   - `name`: The strange or funny name you discovered.
   - `gender`: Gender of the person.(Optional)
   - `variations`: Other variations of name (Optional). Separate names by comma if multiple.
   - `description`: A brief description or context about the name (optional).
   - `origin`: The cultural or geographical origin of the name (optional).
   - `sentiment`: Your sentiment towards the name. It could be subjective, that's fine.(optional) Eg: Humor, Irony, Charm, Cuteness, Intrigue, Surpirse, Fascination, Quirkness, Amusement, Controversy, Admiration, Delight, Nostalgia, Offbeat.
   - `source`: The source or reference where you found the name (optional) Eg: Wikipedia, Stories, Books, Heard From village.
   - **Additonal Field**: You can add your own field as much as possible(optional).
5. If you have multiple names to contribute, create separate JSON files for each one.
6. Commit and push your changes to your forked repository.
7. Open a pull request (PR) to submit your contributions for review.

Please ensure that your contributions adhere to the following guidelines:

- Only submit names that are genuinely funny, strange, or rare.
- Respect privacy and avoid sharing personally identifiable information.
- Avoid offensive or derogatory names. Let's keep the humor light-hearted and inclusive.

## Dataset Format

The dataset is maintained in JSON format to allow flexibility and ease of use. Each JSON file represents a single name entry and contains relevant information about the name. The dataset structure is as follows:


```json
{
  "name": "Ghanshingh",
  "gender": "Male",
  "variations": "Ghane, Ghan Bahadur",
  "description": "The person was a Priest in our village. The      name  is composed of two parts: Ghan (Hammer) + Shingh (Horn)",
  "origin": "Lumbini, Palpa, Nepal",
  "sentiment": "Funny",
  "source": "From Grandparents, heard in the village."
}
```

## Dataset Usage

The dataset provided in this repository is free and open to the public for educational, research, or entertainment purposes. You can access the dataset by cloning this repository or by downloading the specific JSON files of interest. We encourage users to acknowledge and cite this repository if the dataset is utilized in any publications or projects.

## Disclaimer

While we strive to maintain the accuracy and appropriateness of the collected names, the contributors and maintainers of this repository are not responsible for any unintended offense caused by the names listed. Please be mindful and use the dataset responsibly.Please note that the perception of what qualifies as a strange or funny name is subjective and may vary from person to person. What one individual finds amusing, another may not. We encourage contributors and users of this dataset to respect diverse perspectives and understand that humor can be highly personal. The goal of this project is to collect a wide range of names that have garnered attention for their peculiarity or amusement factor. We appreciate the inclusion of names that showcase different cultural backgrounds, linguistic nuances, and unique naming practices.

Remember, the intention is to celebrate the joy and lightheartedness that uncommon names can bring. Let's maintain a positive and inclusive environment throughout our contributions and discussions.

## Acknowledgments

We would like to express our gratitude to all the contributors who have shared their discoveries and made this project possible. Your efforts in expanding this collection of strange and funny names are sincerely appreciated.

## License

This repository is licensed under the [MIT License](LICENSE), allowing you to freely use and modify the dataset for non-commercial purposes. Please refer to the license file for more details.

We look forward to your contributions and hope this dataset brings a smile to your face!

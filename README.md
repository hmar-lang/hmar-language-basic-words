---
license: mit
task_categories:
  - text-classification
  - translation
  - text-generation
  - text2text-generation
language:
  - en
size_categories:
  - 1K<n<10K
---

### Update Notice: Dec-11-2024

The previous dataset has been deleted in light of more accurate and comprehensive translations. This update introduces a better-organized and reliable dataset for the Hmar language, featuring improved translations and formatting. The current dataset includes Dr. John H. Pulamte's dictionary, organized into the **Pherzawl-Diksawnari** folder, with each alphabet stored as its own CSV file. This dataset is part of an ongoing effort to create a comprehensive resource for the Hmar language. Further dictionaries will be integrated in future updates.

## Dataset Card for hmar-language-basic-words

This dataset is part of my personal project to create a comprehensive dataset for the Hmar language. Currently, It includes Dr. John H. Pulamte's dictionary, scraped from [pherzawl-diksawnari.com](https://pherzawl-diksawnari.com/). No explicit license was found on the source website, and users should be aware that this data may be subject to copyright. However, since the data was scraped from a publicly accessible website, I believe it is acceptable for use in **non-commercial purposes**, such as language documentation, learning, and preservation.

The dataset is stored in the `Pherzawl-Diksawnari` directory with CSV files categorized by their starting letter. The previous dataset has been removed in favor of more accurate translations, ensuring this version is a better resource for Hmar language documentation and learning.

This dataset will continue to expand with additional dictionaries and resources as part of a larger effort to document the Hmar language.

### Hmar Language

Hmar is a Sino-Tibetan language spoken by the Hmar people in northeastern India. While not endangered, the language faces challenges in documentation and use, making this project essential for its preservation.

## Dataset Structure

- **Directory:** `Pherzawl-Diksawnari/`
- **File Format:** CSV
- **File Naming:** Each file corresponds to the first letter of the Hmar word (e.g., `a.csv`, `b.csv`, ..., `z.csv`).

### Example File Content

| en         | hmr         |
|------------|-------------|
| Sun        | Nisa        |
| Earth      | Leihnuoi    |
| Mars       | Sikisen     |
| Mercury    | Sikâwlkei   |

## Dataset Details

**Name:** `hmar-lang/hmar-language-basic-words`  
This dataset is part of a broader project to create a comprehensive repository for Hmar language resources.

## Additional Details

##### Standardization Issue

Although this dataset aims to serve as a translation resource, it may not always provide direct word-for-word translations from English to Hmar. In some cases, the dataset includes descriptions or contextual interpretations of Hmar words, reflecting the nuances and cultural significance of the language.

The Hmar alphabet includes the letter "ṭ" (with a dot below), but in this dataset, such words may be represented using "tr" instead. This format follows the conventions used in the **Pherzawl Diksawnari** dictionary by Dr. John H. Pulamte, which is the current source for this dataset. 

You can find these words in the `Pherzawl-Diksawnari` folder. This note is provided to avoid confusion, as future dictionaries integrated into this project (or other datasets) may use the letter "t with a dot" (ṭ) instead of "tr," and this distinction should be kept in mind.

### Sources and Curation

- **Current Sources:** Dr. John H. Pulamte’s Dictionary (scraped from [pherzawl-diksawnari.com](https://pherzawl-diksawnari.com/)).
- **Future Additions:** Additional dictionaries and linguistic resources.

### License

Released under the **MIT License**, but specific data may be subject to copyright.

## Uses

### Intended Uses

- **Language learning:** A resource for English-Hmar translation.
- **Research:** Supporting linguistic studies for the Hmar language.
- **Preservation:** Documenting and safeguarding the Hmar language.
- **NLP:** Building models or tools for machine translation, language understanding, and other NLP tasks related to low-resource languages.

### Limitations

- Focused on basic vocabulary; not suitable for complex tasks or advanced NLP models.

## Related Datasets

- [Hmar Bible Dataset](https://huggingface.co/datasets/hmar-lang/hmar-bible-dataset)  
- [Hmar Language Conversations](https://huggingface.co/datasets/hmar-lang/hmar-language-conversations)

## External Link  
**GitHub:** [Hmar Language Basic Words Repository](https://github.com/hmar-lang/hmar-language-basic-words)

## Extras  
This GitHub repository shares the same structure as the Hugging Face dataset but includes an additional `chunks` folder, where the data is split into four segments. It also contains an unsorted dataset in the root folder named `data.csv`.

## Contact

For inquiries or contributions, please contact us at pheklom@gmail.com

**BibTeX:**
```
@misc{hmar-lang_hmar_language_basic_words,
  author       = {hmar-lang},
  title        = {Hmar Language Basic Words Dataset},
  year         = {2024},
  publisher    = {Hugging Face Datasets},
  howpublished = {\url{https://huggingface.co/datasets/hmar-lang/hmar-language-basic-words}},
  note         = {This dataset is part of a personal project currently being developed as a solo effort.},
  license      = {MIT},
  howpublished = {\url{https://github.com/hmar-lang/hmar_language_basic_words}}
}
```

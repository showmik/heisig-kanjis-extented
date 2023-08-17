# Heisig Kanji Extended

This repository offers an extended dataset of kanji characters featured in James Heisig's book "Remembering the Kanji" 1 & 3. It extends the existing dataset from [this repository](https://github.com/sdcr/heisig-kanjis) by:
- Incorporating 4 new columns (Lesson, Stroke Count, Frequency, and JLPT Level)
- Additionally, it includes 800 missing kanji readings.

## 📦 Contents

The  `heisig-kanjis-extended.csv` file contains the followings:

| Field Name     | Description                                                                   |
| -------------- | ----------------------------------------------------------------------------- |
| kanji          | The kanji itself                                                              |
| id_5th_ed      | The kanji's number in RTK, 5th edition                                        |
| id_6th_ed      | The kanji's number in RTK, 6th edition                                        |
| keyword_5th_ed | The kanji's keyword in RTK, 6th edition                                       |
| components     | The kanji's components                                                        |
| on_reading     | the kanji's On'yomi (On Reading)                                              |
| kun_reading    | the kanji's Kun'yomi (Kun Reading)                                            |
| lesson         | The lesson number in which the kanji is introduced                            |
| stroke         | The number of strokes required to write the kanji                             |
| frequency      | The relative frequency of the kanji's usage in written language               |
| jlpt           | The Japanese Language Proficiency Test (JLPT) level associated with the kanji |

## 🤝 Contribution

If you discover any inaccuracies, missing information, or have suggestions for improvement, feel free to submit an issue or a pull request. Together, we can create a more comprehensive and reliable resource for learners of kanji.

## ✨ Acknowledgments

I extend my appreciation to [sdcr](https://github.com/sdcr) for laying the groundwork for this dataset, and of course, to [James Heisig](https://en.wikipedia.org/wiki/James_Heisig) for providing us with [this](https://www.goodreads.com/en/book/show/749106) remarkable book.

# Jastrow Dictionary Abbreviation Modernizer


A specialized tool for modernizing and enhancing the readability of entries from Marcus Jastrow's "Dictionary of the Targumim, Talmud Bavli, Talmud Yerushalmi and Midrashic Literature" (1903).
Using input text from here:
https://www.sefaria.org.il/Jastrow

## Description

The 100+ year old Jastrow Dictionary is still a valuable resource for Talmudic and rabbinic scholarship, but its entries contain numerous abbreviations, references in Roman numerals, and dense formatting that can make it challenging to read. This tool transforms these entries into more accessible modern format by:

- Expanding abbreviations to their full forms
- Converting Roman numeral references to Arabic format
- Intelligently splitting text into logical paragraphs
- Providing special handling for Hebrew text

## Features

- **Comprehensive Abbreviation Expansion**: Converts 158+ abbreviations commonly used in Jastrow (e.g., "Ber." → "Berakhot", "Ex. R." → "Shemot Rabbah") (beginning with Jastrow's own list: https://www.sefaria.org/Jastrow%2C_List_of_Abbreviations)
- **Citation Format Modernization**: Converts Roman numeral references to Arabic format (e.g., "IV, 6" becomes "4:6")
- **Intelligent Text Structuring**:
  - Splits text into logical paragraphs at source references and semicolons
  - Places Hebrew text in separate paragraphs with right-to-left direction
- **User-Friendly Interface**: Interactive controls with example entries to demonstrate functionality



## Usage

1. Paste a Jastrow Dictionary entry into the input field
2. Configure options:
   - Enable/disable paragraph splitting
   - Enable/disable Hebrew text formatting
3. Click "Process Text"
4. View the modernized text in the output field
5. Review the list of replacements made

## Examples

The tool includes five example entries that demonstrate various features

## Technical Details

The tool employs several advanced techniques:

- Context-aware regex patterns for accurate abbreviation replacement
- Special handling for compound abbreviations
- Hebrew character detection using Unicode ranges
- Right-to-left text formatting for Hebrew sections
- Custom Roman numeral conversion algorithm

## Mapping Dictionary

The tool includes mappings for 158+ abbreviations commonly found in Jastrow's Dictionary, including:

- Tractate abbreviations (e.g., "Ber." → "Berakhot")
- Biblical book abbreviations (e.g., "Gen." → "Genesis")
- Rabbinic works (e.g., "Midr. Till." → "Midrash Tehillim")
- Common Latin phrases (e.g., "q.v." → "which see")
- Grammatical terms (e.g., "pl." → "plural")

## Screenshots

<img width="872" alt="image" src="https://github.com/user-attachments/assets/86b01021-f7bf-4c56-85c6-253ce7054e58" />

<img width="233" alt="image" src="https://github.com/user-attachments/assets/ed6f86c3-e6b0-4416-9110-4d6a46c9f36f" />



Areas for potential improvement:
-fixing bugs
- Additional abbreviations
- Improved paragraph splitting logic
- Enhanced Hebrew text handling

## License



## Acknowledgments

- Marcus Jastrow's Dictionary of the Targumim, Talmud Bavli, Talmud Yerushalmi and Midrashic Literature
- Sefaria.org for their work in digitizing Jewish texts

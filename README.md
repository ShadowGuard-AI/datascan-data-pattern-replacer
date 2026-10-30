![Banner](banner.png)

# datascan-data-pattern-replacer
Identifies and replaces sensitive data patterns (e.g., credit card numbers, phone numbers) with configurable replacement strings or random data. Leverages regular expressions for pattern matching. - Focused on Provides tools to sanitize sensitive data within structured or unstructured data sources. Replaces PII (Personally Identifiable Information) such as names, addresses, phone numbers, and credit card details with realistic, anonymized data using Faker. Supports various data formats like CSV, JSON, and plain text, ensuring data privacy while preserving data utility for testing or development purposes.

Note: --input_format and --output_format must match. The tool reads and writes in the same format and does not convert between text, JSON, and CSV; a mismatched pair is refused with an error instead of writing a mislabeled file.

## Install
`git clone https://github.com/ShadowGuardAI/datascan-data-pattern-replacer`

## Usage
`./datascan-data-pattern-replacer [params]`

## Parameters
- `-h`: Show help message and exit
- `--patterns_file`: Path to the JSON file containing regex patterns and replacements.
- `--use_faker`: Use Faker to generate realistic replacement data.
- `--faker_locale`: No description provided
- `--input_format`: No description provided
- `--output_format`: No description provided

## License
Copyright (c) ShadowGuardAI

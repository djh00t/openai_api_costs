# OpenAI API Costs Tracker

This repository contains up-to-date information on OpenAI API costs for various models. The data is provided in both CSV and Excel (XLSX) formats for easy access and analysis.

## Contents

- `openai_api_costs.csv`: A comma-separated values file containing the latest OpenAI API costs.
- `openai_api_costs.xlsx`: An Excel spreadsheet with the same information as the CSV file, potentially with additional formatting or sheets.

## Data Structure

The CSV file includes the following columns:

- Model: The name of the OpenAI model
- Release Date: The date when the model was released (if known)
- Collected: The date when the pricing information was collected
- Use Case: A brief description of the model's primary use case
- Context Size: The maximum context size for the model (if applicable)
- Knowledge Cutoff: The knowledge cutoff date for the model
- Batch Available: Whether batch processing is available for the model
- Input Cost/1M Tokens: The cost per 1 million input tokens
- Output Cost/1M Tokens: The cost per 1 million output tokens

## Purpose

This repository serves as a centralized location for tracking OpenAI API pricing across different models. It is regularly updated to reflect the most current pricing information whenever new models are released or existing prices change.

## Usage

You can use this data to:
- Compare costs across different OpenAI models
- Plan and budget for AI projects using OpenAI's API
- Track pricing trends over time
- Make informed decisions about which model to use based on cost and capabilities

## Updates

The data in this repository is updated each time new models are released or when there are changes to the pricing structure. The "Collected" column in the CSV file indicates when the information was last updated. Make sure to check for the latest commit or pull the latest changes to get the most up-to-date information.

## Contributing

If you notice any discrepancies between the data in this repository and the official OpenAI pricing, or if you have additional information that could be valuable to include, please:

1. Open an issue describing the discrepancy or suggested addition.
2. Submit a pull request with the corrected or additional information.

Your contributions help keep this resource accurate and valuable for the community.

## Disclaimer

While we strive to keep this information as accurate and up-to-date as possible, always refer to the [official OpenAI pricing page](https://openai.com/pricing) for the most current and authoritative information on API costs. This repository is maintained by the community and is not officially affiliated with or endorsed by OpenAI.

## License

This data is provided for informational purposes only. Please refer to OpenAI's terms of service for any restrictions on the use or distribution of their pricing information. The compilation of this data is made available under the [MIT License](LICENSE.md).

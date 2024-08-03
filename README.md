
# IntelliFile

This project uses a Large Language Model (LLM) to rename files in a specified folder based on their content. The LLM model generates a descriptive and unique name for each file and assigns a category to it. The file is then renamed with the new name and category.

![Logo](https://github.com/user-attachments/assets/0e1f273c-141f-4d46-9a6d-12f3525ee43b)


## Functionality

- Reads the content of each file in the specified folder
- Generates a descriptive and unique name for each file using an LLM model
- Assigns a category to each file using the LLM model
- Renames each file with the new name and category
## Usage

1. Install the required libraries by running pip install -r requirements.txt
2. Set the CATEGORIES environment variable with a comma-separated list of categories (e.g., export CATEGORIES="category1,category2,category3")
3. Place the files to be renamed in a folder named data
4. Run the script using python filereader.py


## Code Structure

The code consists of the following modules:

- read_file: Reads the content of a file based on its extension
- rename_file: Renames a file with a new name and category
- main: Renames files in the specified folder using the LLM model
## Requirements

- Python 3.8+
- pdfminer library for extracting text from PDF files
- ebooklib library for extracting text from EPUB files
- python-docx library for extracting text from DOCX files
- pandas library for data manipulation and analysis
- python-pptx library for extracting text from PPTX files
- langchain library for interacting with the LLM model
- dotenv library for loading environment variables from a .env file
## License

This project is licensed under the [MIT LICENSE](https://github.com/RottenBanana420/IntelliFile/blob/main/LICENSE)


## Authors

- [@RottenBanana420](https://github.com/RottenBanana420)


## Links

[LangChain Documentation](https://api.python.langchain.com/en/latest/langchain_api_reference.html)\
[PDFMiner Documentation](https://pdfminersix.readthedocs.io/en/latest/)\
[EbookLib Documentation](https://docs.sourcefabric.org/projects/ebooklib/en/latest/)\
[Python-Doc Documentation](https://python-docx.readthedocs.io/en/latest/)\
[Pandas Documentation](https://pandas.pydata.org/docs/)\
[Python-Pptx Documentation](https://python-pptx.readthedocs.io/en/latest/)

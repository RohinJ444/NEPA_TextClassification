# NEPA Text Classification Project

This repository contains the Jupyter notebook and associated code for the NEPA text classification project, commissioned by the Union of Concerned Scientists. The project aims to analyze Environmental Impact Statements (EISes) to identify and quantify the impact of various exogenous variables on timelines for federal projects undergoing NEPA (National Environmental Policy Act) review.

## Project Overview

As the Project Manager of a [BEACN](https://www.beacn.org) project commissioned by the Union of Concerned Scientists, I led a team of five associate consultants to conduct a comprehensive analysis of NEPA timelines. In this project, I developed an advanced text classification model to detect so-called exogenous variables (i.e., NEPA-provisioned litigation, mid-project financing issues, third-party construction delays, compliance with the Clean Air Act required, etc.) in lengthy reports formally known as Environmental Impact Statements (EISes) for projects that require federal NEPA review. Our team then used the presence or absence (1 or 0) of each of the exogenous variables in a sample of 300 projects to determine the variables' impact on project durations using regression analysis.

## Technologies Used

- **OCR**: For text extraction from PDFs.
- **Langchain**: For text vectorization.
- **Pinecone**: For server-side storage and vector search.
- **OpenAI API (GPT-4)**: For automated detection of exogenous variables.

## Key Features

- **Text Extraction**: Utilizes OCR to extract text from PDF documents.
- **Text Vectorization**: Employs Langchain for efficient text vectorization.
- **Vector Search**: Uses Pinecone for fast and accurate vector search.
- **GPT-4 Integration**: Leverages the OpenAI API (GPT-4 and text-embedding-3-large) to automatically determine the presence of exogenous variables in environmental impact statements.
- **Automated Data Entry**: Adds binary indicator variables (1 or 0) representing the presence of an exogenous variable to desired destination spreadsheet.

## License

This project is licensed under the MIT License.

## Contact

For any questions or inquiries, please contact [Rohin Juneja](mailto:rohin.juneja@example.com).

## Acknowledgements

We extend our gratitude to the Union of Concerned Scientists for commissioning this project and providing the necessary support.



# NEPA Timelines Analysis Project 

As the Project Manager of a [BEACN](https://www.beacn.org) project commissioned by the Union of Concerned Scientists, I led a team of five associate consultants to conduct a comprehensive analysis of NEPA timelines. The project aims to analyze Environmental Impact Statements (EISes) to identify and quantify the impact of various exogenous variables on timelines for federal projects undergoing NEPA (National Environmental Policy Act) review. 

In this project, I developed an advanced text classification model to detect so-called exogenous variables (i.e., NEPA-provisioned litigation, mid-project financing issues, third-party construction delays, compliance with the Clean Air Act required, etc.) in lengthy reports formally known as Environmental Impact Statements (EISes) for projects that require federal NEPA review. Prior to developing this model, our team conducted extensive research to identify a set of exogenous variables that we hypothesized to affect NEPA project timelines. Our team then used the presence or absence (1 or 0) of each of the exogenous variables in a sample of 300 projects to determine the variables' impact on project durations using regression analysis.

This repository contains a Jupyter notebook and the associated Python code used to develop the text classification model for NEPA timelines described above.

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

## Validation

To validate the accuracy of our text classification model, we conducted a manual classification of exogenous variables on a ssubample of 23 randomly selected projects. The model's classifications were compared against these manual classifications. Our model demonstrated a high level of accuracy, with 20 out of 23 projects showing identical classifications, resulting in an accuracy rate of approximately 87%. Considering the budgetary constraints and the cost-efficiency of the model (approximately $0.40 per project), we are highly satisfied with these results.

## Contact

For any questions or inquiries, please contact [Rohin Juneja](mailto:rohin.juneja@example.com).

## Acknowledgements

I extend my gratitude and sincere thanks to the Union of Concerned Scientists for commissioning this project and providing the necessary support. In particular, I would like to thank David Watkins, Mark Foley, and Pallavi Shrestha for making this project possible.



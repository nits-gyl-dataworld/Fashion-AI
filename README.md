# Fashion Search AI using Myntra Dataset

**Project Description:**  
This project explores the use of semantic search in a fashion context, leveraging the Myntra dataset sourced from Kaggle. The dataset has been customized for this project. For an in-depth overview, refer to the Project Report titled "Fashion Search AI."

The project includes a folder with a sample of 100-200 random images. For access to the full dataset and the original image folder, visit this Kaggle link https://www.kaggle.com/datasets/djagatiya/myntra-fashion-product-dataset


## Objectives:
The primary goal is to create an AI-powered system capable of delivering detailed and user-friendly responses to fashion-related queries. The system is designed to improve user experience by providing contextually relevant information, helping users find fashion items that suit their preferences.

## Design:
The system architecture consists of two primary components: the search layer and the generation layer. The search layer handles the retrieval of relevant fashion items from the dataset based on keywords or set criteria. In contrast, the generation layer utilizes advanced AI models, such as GPT-3.5, to generate comprehensive responses, incorporating context and producing natural language output.

## Implementation:
The implementation process involved several key steps, including data preprocessing, model integration, and the generation of query responses.

### Data Preprocessing:
The CSV dataset was refined to improve data quality and readability.
Missing entries were filled, decimal formats were standardized, and unnecessary columns were eliminated.
Text fields were cleaned to remove HTML tags and extraneous characters.

### Model Integration:
Advanced AI models like GPT-3.5 were integrated to enhance the response generation capability.
Queries were processed through the model to generate contextually rich and detailed responses.

### Query Response Generation:
User queries were handled by both the search and generation layers.
The search layer identified relevant fashion items from the dataset.
The generation layer provided detailed responses, adding contextual understanding and natural language phrasing.


## Challenges:
During implementation, the following challenges were encountered:
Metadata processing complexities.
Issues related to dataset chunking and handling.

## Lessons Learned:
- Proper data preprocessing is crucial for ensuring data quality and readability.
- Integrating advanced AI models can significantly enhance the system's capabilities.
- Handling large datasets requires careful consideration of memory constraints and implementation of efficient data processing techniques.

## Future Scope:
- Implementing the project as a Flask web application.
- Rephrasing prompts and introducing interactive sessions with criteria-based filters.

## Conclusion:
A comparison of the search and generation layers' outputs reveals that the generation layer offers more detailed and comprehensible results. While the search layer effectively retrieves relevant information, the generation layer elevates the quality and readability of the output, making it the preferred choice for providing detailed and user-friendly responses.



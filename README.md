# Marketing Assistant

## Overview
The Marketing Assistant is a Streamlit-based application designed to assist with generating marketing content. The app leverages OpenAI's language model to produce content such as sales copy, tweets, and product descriptions tailored for different age groups.

## Features
- **User-Friendly Interface**: Simple and intuitive UI built with Streamlit.
- **Age-Specific Content**: Generate content tailored for kids, adults, or senior citizens.
- **Content Type Options**: Choose from writing a sales copy, creating a tweet, or writing a product description.
- **Word Limit Slider**: Adjust the word limit for the generated content.
- **Examples-Based Response**: Uses examples to generate contextually appropriate responses.

## Installation

### Prerequisites
- [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- [Python 3.8+](https://www.python.org/downloads/)
- [Streamlit](https://streamlit.io/)

### Step-by-Step Guide

1. **Clone the Repository**
   ```
   git clone https://github.com/your-username/marketing-assistant.git
   cd marketing-assistant
   ```
2. **Create a New Conda Environment**
    ```
    conda create --name marketing-assistant python=3.10
    conda activate marketing-assistant
    ```
3. **Install Required Packages**

    ```
    
    pip install -r requirements.txt
    

    ```
4. **Set Up Environment Variables**
Create a ```.env``` file in the root directory of the project and add your LLM API key:
    ```
    OPENAI_API_KEY=your_openai_api_key_here
    ```
    
5. **Run the Application**

    ```
    streamlit run app.py
    ```
### Usage
1. Open your web browser and go to http://localhost:8501 to access the app.
2. Enter the text you want to generate content for in the text area.
3. Select the type of content you want to generate:
- Sales copy
- Tweet
- Product description
4. Select the target age group:
- Kid
- Adult
- Senior Citizen
5. Adjust the word limit using the slider.
6. Click the "Generate" button to produce the content.
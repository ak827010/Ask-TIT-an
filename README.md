# Ask TIT-an

**Ask TIT-an** is an AI-powered chatbot designed for the Technocrats Institute of Technology, Bhopal. This chatbot aims to address the general queries of students and faculty members, providing assistance not only to existing students but also to alumni and future students. Leveraging a large language model (Generative AI) and information gathered from performance tests, Ask TIT-an ensures efficient and accurate responses.

## Features

- **Course Information and Registration Assistance**: Provides information about available courses, prerequisites, and registration procedures. Guides students through the registration process.
- **Campus Navigation**: Integration with campus maps to help students find their way around campus, locate buildings, classrooms, offices, and other facilities.
- **FAQs and General Information**: Answers frequently asked questions about campus services, academic policies, events, etc., providing instant assistance to students.
- **Financial Aid and Student Services**: Offers assistance with inquiries related to financial aid applications, scholarships, student loans, and access to various student services.

## Technology Used

- **Python**
- **LangChain**
- **Streamlit**
- **Open AI**

## Setup Instructions

### Step 1: Create a Virtual Environment

First, create a virtual environment to ensure that your project's dependencies are isolated. Open your terminal or command prompt and navigate to your project directory, then run:


python -m venv venv

### Step 2: Activate the Virtual Environment
Activate the virtual environment using the following command:

On Windows:  .\venv\Scripts\activate
On macOS and Linux: source venv/bin/activate

### Step 3: Install Dependencies
With the virtual environment activated, install the necessary libraries using pip:
pip install langchain streamlit streamlit_chat streamlit-card pandas openai faiss-cpu faiss-gpu tiktoken

### Step 4: Run the Application
After installing the dependencies, you can run the Streamlit application: streamlit run app.py



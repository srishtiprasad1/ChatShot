# ChatShot

The project is focused on analyzing WhatsApp chats exported in text format. It requires the exported chat to follow a 12-hour time format and should be exported without including media files. The analysis includes various insights such as total messages, word count, media usage, links shared, monthly and daily timelines, activity maps, most active users, word clouds, common words, and emoji analysis.

# Installation and Usage

To run the ChatShot application locally, follow these steps:

1. Clone the repository to your local machine:
   
       git clone https://github.com/srishtiprasad1/ChatShot.git

2. Navigate to the project directory:

       cd ChatShot

3. Install Dependencies:

       pip install -r requirements.txt

4. Run the Application:

       streamlit run ChatShot.py

5. Upload Chat Export File:

       Once the application is running, upload the exported .txt file of your WhatsApp chat using the file uploader on the sidebar.

6. Analyze Your Chat:

       After uploading the chat file, select the user you want to analyze from the dropdown menu on the sidebar and click on "Show Analysis" to view various insights and visualizations.

7. Interact with the Application:

       Explore the different analysis options provided, such as total messages, word cloud, most common words, emoji analysis, and more.

       NOTE : Make sure you have Python installed on your system before following these steps. You can download Python from the official website: python.org.



# Files 

The project consists of three main files:

1. **ChatShot.py**: This is the main code file that contains the Streamlit application for analyzing WhatsApp chats.
   
2. **Preprocessor.py**: This file manages the data preprocessing tasks, including extracting messages and users, and preparing the data for analysis.
   
3. **helper.py**: This file contains helper functions used for various analysis tasks, such as fetching statistics, generating word clouds, and analyzing emojis.

# Libraries Used

The project utilizes the following Python libraries:

**1. Streamlit** : For building interactive web applications.

**2. Pandas** : For data manipulation and analysis.

**3. Matplotlib, Seaborn** : For data visualization.

**4. Regex** : For text pattern matching.

**5. Urlextract** : For extracting URLs from text.

**6. WordCloud** : For generating word clouds.

**7. Emoji** : For working with emojis.

# Contributors

Srishti Prasad

# License

This project is licensed under the [MIT License](LICENSE).


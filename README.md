# Whatsapp_group_Analysis
This repository contains a Python script for analyzing WhatsApp group chat messages. The script extracts data from a WhatsApp chat text file, performs various analyses, and visualizes the results using popular Python libraries. The following analyses are performed:

### Data Preprocessing: The script reads the WhatsApp chat data from the specified file, processes it to extract user messages and timestamps, and organizes the data into a pandas DataFrame.

### Anonymization: To protect the privacy of the group members, the script anonymizes the usernames by assigning them unique identifiers.

### Data Cleaning: The script removes <Media omitted> messages and group notifications from the DataFrame.

### Most Active Users: It identifies the most active users in the group based on the number of messages they have sent.

### Frequently Used Emojis: The script counts and displays the most frequently used emojis in the group messages.

### Sleep Cycle/Active Periods: The script visualizes the distribution of messages per hour to identify the sleep cycle and active periods of the group.

### Word Cloud: A word cloud is generated from the group messages to visualize the most common words used in the chat.

### Sentiment Analysis: The script calculates the average sentiment score of the group messages using the VADER sentiment analysis tool.

### Most Active Users by Number of Days Active: It identifies the users who have been active on the most number of different days in the group.

## How to Use
Requirements: Make sure you have Python installed on your system along with the required libraries mentioned in the requirements.txt file.

 Data Input: Place your WhatsApp chat text file in the same directory as the script and specify its file name in the file_location variable at the beginning of the script.

Run the Script: Execute the script, and it will perform all the analyses on the WhatsApp chat data.

### Results: 
The script will display various plots and analysis results, such as most active users, frequently used emojis, sleep cycle, word cloud, sentiment score, and most active users by number of days active.

## Disclaimer
This script is for educational and research purposes only. Please ensure that you have the necessary permissions to analyze and use the WhatsApp chat data before using this script. The anonymization process is meant to protect privacy, but it's essential to verify the effectiveness of the anonymization and adhere to relevant privacy laws and regulations. The developers of this script are not responsible for any misuse or unauthorized use of this code.

## Contribution
Feel free to contribute to this repository by opening pull requests for bug fixes, new features, or additional analyses that can enhance the WhatsApp group chat analysis.
# Libraries used
NLTK
pandas
scikit learn
emoji
re
collections

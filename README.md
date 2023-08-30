<br/>
<p align="center">
  <h3 align="center">ChatBiz-Analyzer</h3>

  <p align="center"><img src="https://socialify.git.ci/jaikishanmohanty/ChatBiz-Analyzer/image?font=Rokkitt&language=1&name=1&owner=1&pattern=Signal&theme=Light" alt="project-image"></p>

  <p align="center">
    Data-Driven Decisions with ChatBiz Analyzer: Drive Results!
    <br/>
    <br/>
  </p>
</p>



## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
  * [Pull Request](#creating-a-pull-request)
* [Authors](#authors)

## About The Project

ChatBizAnalyzer is a comprehensive and innovative chat analysis tool specifically designed for WhatsApp Business groups. Its primary goal is to empower businesses with deep customer behavior understanding, enabling data-driven decisions and actionable insights for refining marketing strategies. With a robust Exploratory Data Analysis (EDA) approach, this project offers a game-changing solution to enhance customer engagement and boost overall business performance.


![cbz1](https://github.com/jaikishanmohanty/ChatBiz-Analyzer/assets/62710109/12b19751-070e-4514-99c9-f5cba086667c)  ![cbz2](https://github.com/jaikishanmohanty/ChatBiz-Analyzer/assets/62710109/a3735aca-c897-4e4a-a46a-0f1eeb986f0d)
![cbz3](https://github.com/jaikishanmohanty/ChatBiz-Analyzer/assets/62710109/2c3e30c3-926c-4a4b-9a40-38b3f7425db6)  ![cbz4](https://github.com/jaikishanmohanty/ChatBiz-Analyzer/assets/62710109/b2579a24-338d-4506-aca4-ab22759e05c9)
![cbz5](https://github.com/jaikishanmohanty/ChatBiz-Analyzer/assets/62710109/0e3e0f6b-e9d5-4a69-a63e-a32f8f6997d0)  ![cbz6](https://github.com/jaikishanmohanty/ChatBiz-Analyzer/assets/62710109/4b9c1c81-40d6-4dc6-bf08-764871861fe4)
![cbz7](https://github.com/jaikishanmohanty/ChatBiz-Analyzer/assets/62710109/db1cc5b1-7460-48f0-aeba-014b482977df)

<h3>Key Features and Capabilities</h3>
<b>WhatsApp Business Group Analysis:</b> ChatBizAnalyzer specializes in analyzing chat data from WhatsApp Business groups. By leveraging the rich data generated from customer interactions and discussions, businesses can unlock crucial insights that lead to informed decision-making.

<b>Interactive and User-Friendly Interface:</b> This project boasts an elegant and user-friendly interface built using Streamlit, a state-of-the-art Python library. The intuitive design ensures effortless navigation and smooth data analysis, making it accessible to both technical and non-technical users.

<b>Captivating Data Visualizations:</b> Harnessing the power of Matplotlib, ChatBizAnalyzer generates captivating graphs and visualizations. These graphical representations enable businesses to identify trends, patterns, and customer sentiments at a glance, facilitating a deeper understanding of customer behaviour.

<b>Wordcloud Generation for Enhanced Insights:</b> The Wordcloud library is skillfully integrated into the project, allowing the creation of visually appealing wordclouds based on the most frequently used words in customer conversations. These wordclouds offer a unique way to grasp the most prominent topics and keywords in the chat data.

<h3>How to Use</h3>
<b>Data Collection:</b> Export the chat data from your WhatsApp Business group in the required format (e.g., .txt or .csv) and save it to a designated folder.

<b>Setting Up:</b> Clone the ChatBizAnalyzer repository and install the necessary dependencies using the provided requirements file.

<b>Launch the Interface:</b> Run the Streamlit application by executing the appropriate command. This will open up a web-based interface for data analysis.

<b>Load Data:</b> Within the interface, browse and load the exported chat data from your WhatsApp Business group.

<b>Explore Insights:</b> Once the data is loaded, you can start exploring various insights and trends in the chat using the provided interactive visualizations and wordclouds.

## Built With

<ul>
<li>python(3.10)</li>
<li>streamlit</li>
<li>wordcloud</li>
<li>matplotlib</li>
<li>pandas</li>
<li>urlextract</li>
<li>emoji(1.7.0)</li>
</ul>

## Getting Started

Welcome to ChatBizAnalyzer! This project is a powerful tool designed specifically for WhatsApp Business groups to gain valuable insights into customer behavior and enhance marketing strategies through Exploratory Data Analysis (EDA). With an interactive interface and captivating visualizations, ChatBizAnalyzer empowers businesses to make data-driven decisions and optimize customer engagement.

### Prerequisites

Before you get started with ChatBizAnalyzer, ensure you have the following prerequisites installed on your system:

<b>Python:</b> Make sure you have Python installed on your computer. ChatBizAnalyzer requires Python 3.6 or later to run. If you don't have Python installed, you can download it from the official website: Python Downloads.

<b>pip:</b> pip is the package installer for Python, and it comes bundled with Python versions 3.4 and above. Check if pip is installed by running the following command in your terminal or command prompt:

```sh
pip --version
```
If pip is not installed, you can install it using the Python installer by following the instructions on the pip documentation.

### Installation

Follow these steps to set up ChatBizAnalyzer on your local machine:

<b>Clone the Repository:</b> Clone the ChatBizAnalyzer repository to your desired location on your computer using Git or by downloading the repository as a ZIP file and extracting it.
```sh
https://github.com/jaikishanmohanty/ChatBiz-Analyzer.git
```

<b>Create a Virtual Environment (Recommended):</b> It is best practice to create a virtual environment for ChatBizAnalyzer to isolate its dependencies from other projects. Navigate to the project's root directory and create a virtual environment by running:
```sh
# Windows
python -m venv venv

# macOS/Linux
python3 -m venv venv
```
<b>Activate the Virtual Environment:</b> Activate the virtual environment to use the isolated Python environment with required dependencies:

```sh
# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```
<b>Install Dependencies:</b> Use pip to install the necessary dependencies from the requirements.txt file:

```sh
pip install -r requirements.txt
```

## Usage

ChatBizAnalyzer provides various insightful analyses and visualizations to help you understand customer behaviour and optimize marketing strategies. Here's an overview of the key features and how to use them:
<ul>
<li><b>Top Statistics Displayed:</b> Get a quick overview of essential statistics related to your WhatsApp Business group, such as the total number of messages, the number of unique users, the most active users, and more.</li>

<li><b>Monthly Timeline Graph:</b> Explore the chat activity trends over months using the monthly timeline graph. This visualization allows you to identify peak activity periods and spot any significant changes in customer interactions.</li>

<li><b>Daily Timeline Graph:</b> The daily timeline graph provides a detailed view of chat activity on a daily basis. Observe the daily fluctuations and uncover patterns in customer engagement throughout each day.</li>

<li><b>Most Busy Day:</b> Discover the day with the highest chat activity in your WhatsApp Business group. This information can help you focus marketing efforts and customer support on days with the most engagement.</li>

<li><b>Most Busy Month:</b> Identify the month with the highest chat activity. Understanding the most active month can assist in planning targeted campaigns and promotions.</li>

<li><b>Weekly Activity Map:</b> Get a clear representation of weekly chat activity with the weekly activity map. This visualization allows you to visualize the busiest days of the week and patterns over time.</li>

<li><b>Most Busy Users:</b> Find out the most active users in your WhatsApp Business group. Knowing the most engaged users can help you reward loyal customers and identify potential brand ambassadors.</li>

<li><b>Wordcloud and Most Common Words:</b> Generate a visually appealing wordcloud based on the most frequently used words in customer conversations. Additionally, explore a list of the most common words to gain insights into popular topics and trends.</li>

<li><b>Emoji Analysis:</b> Gain an understanding of customer sentiments and emotions by analyzing emoji usage in the chats. Emoji analysis can provide valuable insights into the overall mood and sentiment of your customer interactions.</li>
</ul>
To use ChatBizAnalyzer, follow the installation steps mentioned in the "Installation" section of the README. Once set up, launch the application using the command streamlit run app.py in your terminal or command prompt. Load the exported chat data from your WhatsApp Business group, and start exploring the various visualizations and analyses to gain actionable insights for your marketing strategies. Happy analyzing! 😊

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/jaikishanmohanty/ChatBiz-Analyzer/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Authors

* **Jaikishan Mohanty** - *Software Engineering Student* - [Jaikishan Mohanty](https://github.com/jaikishanmohanty)

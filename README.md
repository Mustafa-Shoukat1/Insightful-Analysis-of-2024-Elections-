# Insightful-Analysis-of-2024-Elections-

<div style="border-radius: 20px; border: 2px solid #64B5F6; padding: 15px; background-color: #6A0DAD; text-align: center; box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.4), 0px 6px 20px rgba(0, 0, 0, 0.19); transform: perspective(1000px) rotateX(5deg) rotateY(-5deg); transition: transform 0.5s ease-in-out;">
    <h1 style="color: #FFFFFF; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4); font-weight: bold; margin-bottom: 10px; font-size: 32px;">
        Welcome!
    </h1>
    <p style="color: #FFFFFF; font-size: 18px; margin: 10px 0;">
        Hi there! I'm Maryam Shoukat, a dedicated Data Analyst in training. I'm deeply immersed in the world of AI, exploring various concepts and techniques to enhance my skills. Join me on this exciting journey as we learn and grow together in the field of AI.
    </p>
    <p style="color: #FFFFFF; font-size: 16px; font-style: italic; margin: 10px 0;">
        "Community empowers growth through shared knowledge and mutual support."
    </p>
    <h2 style="color: #FFFFFF; margin-top: 15px; font-size: 28px;">Contact Information</h2>
    <table style="width: 100%; margin-top: 15px; border-collapse: collapse;">
        <tr>
            <th style="color: #FFFFFF; font-size: 18px; padding: 8px; border-bottom: 2px solid #FFFFFF;">Name</th>
            <th style="color: #FFFFFF; font-size: 18px; padding: 8px; border-bottom: 2px solid #FFFFFF;">Email</th>
            <th style="color: #FFFFFF; font-size: 18px; padding: 8px; border-bottom: 2px solid #FFFFFF;">LinkedIn</th>
            <th style="color: #FFFFFF; font-size: 18px; padding: 8px; border-bottom: 2px solid #FFFFFF;">GitHub</th>
            <th style="color: #FFFFFF; font-size: 18px; padding: 8px; border-bottom: 2px solid #FFFFFF;">Kaggle</th>
        </tr>
        <tr>
            <td style="font-size: 16px; padding: 8px;">Maryam Shoukat</td>
            <td style="font-size: 16px; padding: 8px;">mustafashoukat.ai@gmail.com</td>
            <td style="font-size: 16px; padding: 8px;">
                <a href="https://www.linkedin.com/in/mustafashoukat/" target="_blank">
                    <img src="https://img.shields.io/badge/LinkedIn-0e76a8.svg?style=for-the-badge&logo=LinkedIn&logoColor=white" alt="LinkedIn Badge" style="border-radius: 5px;">
                </a>
            </td>
            <td style="font-size: 16px; padding: 8px;">
                <a href="https://github.com/Mustafa-Shoukat1" target="_blank">
                    <img src="https://img.shields.io/badge/GitHub-171515.svg?style=for-the-badge&logo=GitHub&logoColor=white" alt="GitHub Badge" style="border-radius: 5px;">
                </a>
            </td>
            <td style="font-size: 16px; padding: 8px;">
                <a href="https://www.kaggle.com/mustafashoukat" target="_blank">
                    <img src="https://img.shields.io/badge/Kaggle-20beff.svg?style=for-the-badge&logo=Kaggle&logoColor=white" alt="Kaggle Badge" style="border-radius: 5px;">
                </a>
            </td>
        </tr>
    </table>
</div>




![image](https://th.bing.com/th/id/OIP.4vh53qUvzUsvUXQjv0-MHQAAAA?rs=1&pid=ImgDetMain)



<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">About the Dataset</h1>

<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Introduction</h1>

 Welcome to the comprehensive analysis of Pakistan's political constituencies dataset! 🎉 This dataset provides an insightful look into the regions, constituencies, members, and their respective political parties in Pakistan. It's an excellent resource for understanding the political landscape and the distribution of political members across different regions.

<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Dataset Overview</h1>


This dataset comprises **266 rows** and **4 columns**, each representing a specific constituency with related details:

- **Region**: The province or region in Pakistan where the constituency is located (e.g., Balochistan, Sindh).
- **Constituency**: The specific constituency identifier along with its name (e.g., NA-266 Killa Abdullah-cum-Chaman).
- **Member**: The name of the member representing the constituency.
- **Party**: The political party to which the member belongs (e.g., PKMAP, JUI(F), PPP).

<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Data Source</h1>

This dataset was sourced from [Kaggle](https://www.kaggle.com) and has been meticulously analyzed to uncover various trends and insights. The original dataset can be found [here](https://www.kaggle.com).

<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Missing Values</h1>


The dataset contains some missing values, particularly in the 'Member' and 'Party' columns. Approximately **21%** of the values are missing, which were handled appropriately during the analysis process.

<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Purpose of Analysis</h1>


The primary objective of this analysis is to visualize the distribution of political members by region and party, and to understand the political landscape in Pakistan's constituencies. Various visualizations have been created using Plotly to illustrate these distributions and relationships.
<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Analysis Summary</h1>


Here’s what you can expect from this notebook:

- **Distribution of members per region**: Understanding how political members are distributed across different regions.
- **Distribution of members per party**: A look into which parties have more representation.
- **Relationship between regions and parties**: Analyzing how different parties are represented in various regions.

<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Why This Notebook?</h1>


This notebook stands out because it not only provides a detailed analysis but also engages the reader with interactive visualizations. It's designed to be informative and visually appealing, making data exploration a delightful experience.

<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Let's Dive In! 🚀</h1>



Join me in exploring the political dynamics of Pakistan through this data. Whether you are a data enthusiast, a political analyst, or just curious, this notebook has something for everyone. Happy analyzing!



<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Data Cleaning 🧹</h1>

# Visualize missing values using a heatmap
plt.figure(figsize=(8,4))
sns.heatmap(df.isnull(),yticklabels=False,cbar=False,cmap="viridis")

![image](https://github.com/Mustafa-Shoukat1/Insightful-Analysis-of-2024-Elections-/assets/162743520/4d80b67c-6110-4129-80ca-cf5812158125)


<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">Exploratory Data Analysis (EDA) 📊</h1>

#  Number of unique values in each column

![image](https://github.com/Mustafa-Shoukat1/Insightful-Analysis-of-2024-Elections-/assets/162743520/1284ddaf-5361-48be-8a11-0e46352fc14b)




<h1 style="color: #6a0dad; font-family: 'Times New Roman', Times, serif;">📊 Visualization 📊</h1>


Plotted the count of members per region using Plotly Express and matplotlib.
Plotted the count of members per party using Plotly Express.
Created a pie chart showing the distribution of regions in constituencies.
Plotted a bar chart showing the distribution of members by party in different regions using Plotly Express.
Created a Group bar chart to visualize the relationship between regions and parties.




![image](https://github.com/Mustafa-Shoukat1/Insightful-Analysis-of-2024-Elections-/assets/162743520/6789003a-7ada-4dca-8ea9-c81efd599cf6)



![image](https://github.com/Mustafa-Shoukat1/Insightful-Analysis-of-2024-Elections-/assets/162743520/248d979e-32ef-4970-b1f7-220898e694cd)



![image](https://github.com/Mustafa-Shoukat1/Insightful-Analysis-of-2024-Elections-/assets/162743520/5a10ac93-edf9-445d-8852-9637dec4f8c0)


![image](https://github.com/Mustafa-Shoukat1/Insightful-Analysis-of-2024-Elections-/assets/162743520/15decd8f-3f48-4256-b57d-17f1e19be040)



![image](https://github.com/Mustafa-Shoukat1/Insightful-Analysis-of-2024-Elections-/assets/162743520/e9ab5854-9775-4002-9cac-59ea2d52e7e0)




# Question:
# Q1: Which region in Pakistan has the highest number of members?
    
Answer:
The region with the highest number of members is Punjab, which reflects its significant political representation compared to other regions in Pakistan.



# Question:
# Q2: Which political party in Pakistan has the highest number of members?

Answer:
The party with the highest number of members is Independent. This indicates significant representation from independent candidates across various constituencies in Pakistan.



# Question:
# Q3: In which region was the voter turnout the highest?

Answer: Voter turnout was highest in Punjab, reflecting strong civic engagement in that region.




# Questions
# Q4: How many political parties are there in each region of Pakistan (Punjab, KPK, Sindh, ICT, Balochistan) and what are their names?

## Balochistan:
8 parties, including PKMAP, JUI(F), PPP, PML(N), Independent, BNP-M, National Party, and PKNAP.
## Islamabad Capital Territory (ICT):
2 parties, Independent and PML(N).
## Punjab:
7 parties, including Independent, PML(N), PML(Q), PPP, IPP, and PMLN(N).
## Sindh:
3 parties, including MQM-P, PPP, and PPPP.
## Khyber Pakhtunkhwa (KPK):
5 parties, including Independent, PPP, JUI(F), Majlis Wahdat-e-Muslimeen, and PML(N).




## Data-Driven Decision:
Using insights from the dataset on Pakistan's political constituencies, data-driven decisions aim to optimize campaign strategies, enhance policy development, promote civic engagement, and allocate resources strategically. This approach ensures more effective, equitable, and transparent political processes in Pakistan.



<div style="border-radius: 20px; border: 2px solid #64B5F6; padding: 15px; background-color: #673AB7; text-align: center; box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.4), 0px 6px 20px rgba(0, 0, 0, 0.19); transform: perspective(1000px) rotateX(5deg) rotateY(-5deg); transition: transform 0.5s ease-in-out;">
    <h1 style="color: #FFFFFF; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4); font-weight: bold; margin-bottom: 10px; font-size: 36px;">
        Thanks! 🌟
    </h1>
    <h2 style="color: #FFFFFF; font-size: 24px; margin-top: 10px;">
        Your Support Matters
    </h2>
    <p style="color: #FFFFFF; font-size: 18px; margin: 10px 0;">
        Thank you for visiting my page! I appreciate your support and interest in my journey as a Data Analyst.
    </p>
    <p style="color: #FFFFFF; font-size: 16px; font-style: italic; margin: 10px 0;">
        "Your encouragement fuels my passion for learning and growth."
    </p>
    <div style="background-color: #512DA8; padding: 10px; border-radius: 10px; margin-top: 15px;">
        <h3 style="color: #FFFFFF; font-size: 20px; margin: 5px 0;">
            Join Me on This Journey! 🚀
        </h3>
        <p style="color: #FFFFFF; font-size: 16px; margin: 5px 0;">
            Let's explore AI and Data Analysis together. Together, we can unlock insights and create meaningful impact.
        </p>
    </div>
</div>










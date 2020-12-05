# Universities Ranking

In this project we present in an interactive way the Universities Ranking presented by Times Higher Education in Partnershio with Elsevier. This is done by webscraping the site "https://www.timeshighereducation.com/world-university-rankings/2021/world-ranking#!/page/0/length/25/sort_by/rank/sort_order/asc/cols/stats".

The Times Higher Education World University Rankings are the only global performance tables that judge research-intensive universities across all their core missions: teaching, research, knowledge transfer and international outlook. It is used 13 performance indicators to provide the most comprehensive and balanced comparisons, trusted by students, academics, university leaders, industry and governments.

The performance indicators are grouped into five areas: Teaching (the learning environment); Research (volume, income and reputation; Citations (research influence); International outlook (staff, students and research); and Industry income (knowledge transfer). [cite: https://www.timeshighereducation.com/world-university-rankings/world-university-rankings-2021-methodology]

In the following image (fro the cite[]), it is described how does each indicator is agregated into another indicator to finally obtain an overall score 
[image]

## The objective
The project's objective is to use the THE information in order to design a web page that might be useful to any student in the world that might be interestes in studying abroad.

## Data collection and transformation
The data from the THE website is not available to download it from api or as a csv, therefore, web scraping techniques are used to obtain a series of indicators. The webscraping is done using Python, and data was kept as a Pandas dataframe. The indicators collected through webscraping were the five principal ones and some that might be of interest for an international student.

1. Citations score

2. Gender Ratio

3. Industry income score

4. International outlook score

5. Industry income score

6. Number of students

7. Overall_score

8. Percentage of international students. 

9. Ranking

10. Research Score

11. Students to staff ratio

12. Teaching score

13. Title (The neme of the University).

Eventhoug the Name of the University was obtained, no information about its location was gathered. Thus, it was necessary to obtain the data from other source. We opted to use Google's geocoding api to retrieved the latitude and longitude of each 
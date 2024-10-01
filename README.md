# G2-Esport-Data-Analysis
Esport Performance Data Analysis and Visualization

## Project Overview
This data analysis project aims to provide insights into G2 Esports' performance in the LEC throughout 2024. By examining game data, I seek to gain a deeper understanding of G2's playstyle, the factors contributing to their competitiveness, and the strengths and weaknesses of their players. Additionally, I hope to foster greater engagement between G2 fans and their favorite team, helping them to better know the players through the lens of data.

## Link to Project's Dashboard
https://public.tableau.com/app/profile/tashi.delek/viz/G2_17271748175650/StaticDashboard

## Data Source
Dataset was obtained in csv file from https://oracleselixir.com/tools/downloads, which is maintained and updated daily by Tim Sevenhuysen.

## Tools
- Excel - For data cleaning and wrangling
- Tableau - For data analysis and visualization

## Data Preparation Process
### In Excel
1. Deleting all the columns that contain ONLY null values.
2. Filtering out the records of team performance, since I wanted the dataset to be at the individual player's level of granularity. Copying these team records into a separate file and deleting them from the original dataset, leaving only individual player's records - each row represents a unique player-game combination.
3. Filling up the missing values in the player name column by taking educated guess (referring to the similar records)
4. Adding two more columns that store the value of opponent player anme and opponent champion for each individual record. This allows me to do opponent analysis, for example, finding out which opponent champions have led to G2 losing the games.
### In Tableau
Apply the data source filter to filter out only the LEC regions, since my goal was to analyze G2's performance within the LEC region.

## Data Analysis and Visualization

I created more than 15 visuals in total to explore G2’s team style and explanation in text to help viewers better understand them.
I put 10 of them into a dashboard that offers a high-level overview of G2's performance.

Bar charts displaying the most picked champions by G2 in LEC over the year of 2024.

  ![image](https://github.com/user-attachments/assets/6fc01ce8-8173-4e7f-9753-435d8f45458d)

A scatterplot illustrating the relationship between average gold share and average damage share. Each dot represents a unique player-champion combination, highlighting how effectively players convert team gold into team damage with different picks. High-conversion picks are colored in red, while low-conversion picks are shown in pink.

  ![image](https://github.com/user-attachments/assets/9fe42189-0900-462e-84d4-614402a509be)

A heat map showcasing opponent champion picks that have contributed to G2's low win rate. Hover over each cell to reveal the game ID and the corresponding champion match-up.

  ![image](https://github.com/user-attachments/assets/8f06cc92-0490-4ce8-a1f8-88f6c80baf07)

Bar chart that counts the champion pool of each G2 player

  ![image](https://github.com/user-attachments/assets/47095283-e91b-4e3d-a373-bb19f1026893)

Bar chart that shows the average KDA of each G2 player

  ![image](https://github.com/user-attachments/assets/74dd9990-62c2-48c1-9afc-51d590078c9a)

Three heat maps standing together to display the average CS difference, average experience difference, and average death of each G2 player in 10,15,20,and 25 minutes, respectively.

  ![image](https://github.com/user-attachments/assets/a57597d1-841b-40e9-b50a-ac8cd87aeb54)

Four banners highlighting key metrics of G2's performance and their standings in the league.

  ![image](https://github.com/user-attachments/assets/ce69f31c-0712-48e3-8678-b02d10e6641c)


Numerous heat maps displaying player metrics across all positions. These charts compare G2 players to their counterparts in the same position within the LEC and display the champions and players effectiveness in different match-ups that offer valuable information in the ban-pick strategies. These graphs are not included in the dashboard but will be explained in the section below.

## Findings/Recommendations

1.   G2 has a strong preference for champions that can initiate fights effectively. This tendency extends even to their ADC picks, with champions like Ashe, Varus, and Kalista, all of whom can significantly influence team fights. These champions offer crucial CC and utility, allowing G2 to engage or disengage strategically. This approach not only enhances their aggressive playstyle but also ensures that they can dictate the pace of the game, making them a formidable opponent on the Rift.

2. Broken Blade is an incredibly flexible player and a secret weapon for G2. He boasts the deepest champion pool on the team, having played 21 different champions in the LEC 2024. His diverse selections allow him to present unexpected challenges to opponents. While he often starts games behind his opponents in terms of CS and XP, he has the ability (maybe with the help of Yike) to close those gaps and eventually outpace them in the late game. Additionally, Broken Blade ranks third among the league top laners for average damage to champions while surprisingly maintaining the lowest average death rate. This combination of resilience and damage output makes him a great value for G2.

      ![image](https://github.com/user-attachments/assets/221c9a77-77ad-4f76-89fe-570d4b3d6c87) ![image](https://github.com/user-attachments/assets/105ae1b8-9605-4f6a-bc75-651de383b738)


3. Yike is an absolute beast, often overshadowed by G2's two primary carries. Not only does he have the highest average KDA on the team, but he also leads all junglers and ranks second among all players in the league. Additionally, he tops the charts in average assists, average damage to champions, and average kills among junglers in the LEC. While he may not have the flashiest champion pool, Yike is undeniably one of the most effective junglers and a cornerstone of stability for G2. His contributions help anchor the team, allowing the carries to shine while maintaining a consistent and impactful presence in games.

      ![image](https://github.com/user-attachments/assets/75f1f6dc-cee9-43cb-a888-7196a7b7a2a8)

4. When it comes to converting team gold into team damage, Hans Sama's Kog'Maw shows promise, even with a small sample size of just one game. However, his Draven hasn't been as effective, with a sample of four games to consider. Other high-performing picks include Caps’s Aurelion Sol and Veigar, Broken Blade’s Yone, Hans Sama’s Smolder, and Mikyx’s Neeko. In contrast, Caps’ Yasuo falls into the low damage conversion category, likely chosen for strategic purposes or simply for ENTERTAINMENT! This blend of serious and fun picks highlights G2's dynamic playstyle, keeping both opponents and fans on their toes!

5. Caps and Hans Sama are undeniably the primary damage generators for G2. Caps boasts the second-highest average damage to champions and the second-best KDA among mid laners, trailing only Humanoid. His most frequently played champions, such as Corki, Azir, and Tristana, are late-game carries that ensure significant damage output. However, Caps also surprises opponents with picks like Ezreal and even K'Sante, showcasing his versatility.

      ![image](https://github.com/user-attachments/assets/18c75d55-2e80-4cf4-a017-f7ce7931cca7)

6. Hans Sama, on the other hand, tends to choose champions that offer greater strategic value and CC. He is the team's top damage dealer, but thanks to the damage output ability from his teammates, he can afford to pick champions that are flexible and focus on strategic contributions as well. This dynamic allows G2 to maintain a well-rounded approach, making them a formidable force in any matchup.

     ![image](https://github.com/user-attachments/assets/d6ae29b8-8c06-4ad2-a7e4-06a4e00ea1c2)

7. G2 has a low win rate when facing some champions, such as Nidalee and Ornn. Some of these opponent picked champions are naturally advantageous in lane and picked as a counter, but it is definitely worth investigating the composition and in-game performance of these match-ups. For example, Azir has an average advantage both in terms of CS and XP when facing Hwei across LCS, LEC, and LCK. However, Caps' Azir has a sudden drop in XP at 15 minute when facing Hwei, which was due to 3 consecutive loss in skirmishes from 10 to 15 minutes periods if we watch the replay. From the heat map we can also see that Yone is a super effective and dominant champion against both Hwei and Ornn.
   
    ![image](https://github.com/user-attachments/assets/508cf6b8-e7b7-407e-b35b-e176065baad1)
   ![image](https://github.com/user-attachments/assets/eaddac09-5d50-475e-8694-3d0d2298d307)

   ![image](https://github.com/user-attachments/assets/ccecbb36-5142-41af-9bf1-7b385e7cc160)

   
9. Mikyx may appear underwhelming on the heat map due to his high death count, but this can be attributed to his exceptional ward placements and vision score, both of which rank second in the league. He also boasts the second-highest average assists and the third-highest damage to champions among supports. Surprisingly, he has the highest gold earned among supports in the LEC. However, Mikyx's high average death count may stem from his bold positioning choices. He needs to be particularly mindful of his positioning in the mid to late game, as even a small mistake can lead to his untimely demise. These metrics highlight that Mikyx is not just a player with a flashy playstyle; he contributes significantly to his team's success, making him as intriguing as BrokenBlade. His ability to balance aggression with strategic vision sets him apart as a key asset for G2.

     ![image](https://github.com/user-attachments/assets/730c16e7-c515-4f75-a6c4-e051e218d7a6)

    
Finally, the claim that G2 is the most entertaining League of Legends team is no joke. In 2024, G2 players showcased an impressive diversity, playing a total of 82 unique champions. This wide range not only captivates fans but also creates significant challenges for their opponents.
G2's roster features players with complementary yet distinctive styles. Each member contributes damage across various champion selections, even Mikyx, granting the team exceptional flexibility in drafts. Their unpredictability can catch opponents off guard, while more consistent players serve as reliable cornerstones for the team.
I would describe G2 as "fancy" in a way that is both strategic and engaging. This blend of unpredictability and consistency is what sets G2 apart and makes them consistently competitive and entertaining!



## Limitation
Most data points in the visualization have small sample sizes, which may exaggerate certain trends. For instance, champions played only once can lead to misinterpretation. It’s important to remember that data represents only part of the story; factors such as coaches' and players' experience, intuition, and even the quality of sleep before a game also play crucial roles. Therefore, while data can greatly enhance our understanding of esports, it can equally blind us if we are not careful enough.

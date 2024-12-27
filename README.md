# Fifa20-Clustering
![image](https://github.com/Tanwar-12/Fifa20-Clustering/assets/110081008/50d9cd97-ab19-4a8c-99b8-3fe9cf7476dc)

## Overview :
FIFA 20 is a football simulation video game published by Electronic Arts as part of the FIFA series. It is the 27th installment in the FIFA series, and was released on 27 September 2019 for Microsoft Windows, PlayStation 4, Xbox One, and Nintendo Switch.
## BUISNESS CASE: WITH THE FIFA20 DATASET WE NEED TO CLUSTER THE PLAYER BY THEIR SKILL INTO CERTAIN GROUP

### TASK: CLUSTERING
Here’s a more concise, bullet-pointed version of your content:

---



### **Domain Analysis of Features:**
- **SOFIFA-ID**: Unique player ID.
- **PLAYER URL**: Web address of player profile.
- **SHORT NAME**: Nickname of the player.
- **LONG NAME**: Full player name.
- **AGE**: Age of the player.
- **DOB**: Date of birth.
- **HEIGHT CM**: Height in cm.
- **WEIGHT KG**: Weight in kg.
- **NATIONALITY**: Country of origin.
- **CLUB**: Football team.
- **OVERALL**: Player’s total rating.
- **POTENTIAL**: Future potential rating.
- **VALUE EUR**: Player value in EUR.
- **WAGE EUR**: Player’s wage in EUR.
- **PLAYER POSITIONS**: Field position.
- **PREFERRED FOOT**: Foot dominance.
- **INTERNATIONAL REPUTATION**: International rating (1-5 stars).
- **WEAK FOOT**: Rating of non-preferred foot.
- **SKILL MOVES**: Skill complexity (1-5).
- **WORK RATE**: Effort levels in field positions.
- **BODY-TYPE**: Player’s physical build.
- **REAL FACE**: Real-life face scan.
- **RELEASE CLAUSE EUR**: Minimum price to release.
- **PLAYER TAGS**: Identified skill tags (e.g., Dribbler, Speedster).
- **TEAM POSITION**: Player’s team position.
- **TEAM JERSEY NUMBER**: Player’s team number.
- **LONED FROM**: Temporary player loan.
- **JOINED**: Date of club joining.
- **CONTRACT VALID UNTIL**: Contract end year.
- **NATION POSITION**: National team position.
- **NATION JERSEY NUMBER**: National team number.
  
**Player Skills:**
- **PACE**: Speed of the player.
- **SHOOTING**: Shooting accuracy.
- **PASSING**: Passing ability.
- **DRIBBLING**: Ball control skills.
- **DEFENDING**: Defensive ability.
- **PHYSIC**: Physical endurance and strength.
- **GK (Goalkeeping)**: Various stats (e.g., diving, handling, reflex).
  
**Mental & Defensive Attributes:**
- **MENTALITY**: Includes aggression, vision, composure.
- **DEFENDING**: Skills like standing & sliding tackle.

**Football Position Abbreviations:**
- **LS, ST, RS, LW, CF, RW, etc.**: Position abbreviations for attackers, midfielders, and defenders.

---

## **Exploratory Data Analysis:**
1. **Top 10 Nationalities by Player Count**.
2. **Top 10 Clubs by Player Count**.
3. **Top 10 Team Positions**.

## **Data Processing & Feature Engineering:**
- **Impute Missing Values**: Using median.
- **Handle Categorical Data**: Manual encoding.
- **Outlier Handling**: Using IQR and Empirical rule.
- **Scaling**: Min-Max scaling.
- **Feature Selection**: Remove constants, highly correlated features, and apply PCA.

## **Model Creation & Evaluation:**
- **Clustering**: K-means algorithm.
- **3 Clusters**: Silhouette score: 0.61.
- **5 Clusters**: Silhouette score: 0.50.



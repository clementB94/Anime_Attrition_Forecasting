# Anime_Attrition_Forecasting

## 1 - Attrition

Le [taux d'attrition ](https://www.definitions-marketing.com/definition/Taux-d-attrition/) représente le pourcentage de clients perdus, quelle qu'en soit la raison, pour une durée définie. 
Prédire l'attrition permet de (i) tenter d'y remédier par un marketing ciblé, (ii) comprendre les ressorts du départ de clients et tenter de corriger ces causes.. 

On examinera ici ce problème dans le cas d'un service de cartes bancaires, où il s'agit de prédire quels clients vont résilier leur service. Il s'agit donc d'un problème de <u>discrimination</u> dans lequel nous allons devoir prédire la classe de "Attrition".

**Description**

- Client: Unique identifier for the customer holding the account
- Attrition: Internal event (customer activity) variable -Existing customer/Attrited customer
- Customer_Age: Demographic variable - Customer's Age in Years
- Gender: Demographic variable - M=Male, F=Female
- Dependent_count: Demographic variable - Number of dependents
- Education_Level: Demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)
- Marital_Status: Demographic variable - Married, Single, Divorced, Unknown
- Income_Category: Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown)
- Card_Category: Product Variable - Type of Card (Blue, Silver, Gold, Platinum)
- Months_on_book: Period of relationship with bank
- Total_Relationship_Count: Total no. of products held by the customer
- Months_Inactive_12_mon: No. of months inactive in the last 12 months
- Contacts_Count_12_mon: No. of Contacts in the last 12 months
- Credit_Limit: Credit Limit on the Credit Card
- Total_Revolving_Bal: Total Revolving Balance on the Credit Card
- Avg_Open_To_Buy: Open to Buy Credit Line (Average of last 12 months)
- Total_Amt_Chng_Q4_Q1: Change in Transaction Amount (Q4 over Q1)
- Total_Trans_Amt: Total Transaction Amount (Last 12 months)
- Total_Trans_Ct: Total Transaction Count (Last 12 months)
- Total_Ct_Chng_Q4_Q1: Change in Transaction Count (Q4 over Q1)
- Avg_Utilization_Ratio: Average Card Utilization Ratio


## 2 - Anime

On s'intéresse ici à comprendre quels sont les ingrédients qui conduisent au succès d'un "anime". Les données sont issues du site https://www.anime-planet.com. 
On dispose d'un ensemble de données sur les anime, et l'objectif est de construire un modèle permettant de prédire le score, variable *rating*. On utilisera donc une régression linéaire, pour laquelle on va analyser et préparer les données, sélectionner les variables pertinentes, mesurer les performances. 

**Description**
- title: title of anime
- mediaType: format of publication
- eps: number of episodes (movies are considered 1 episode)
- duration: duration of episode
- ongoing: whether it is ongoing
- startYr: year that airing started
- finishYr: year that airing finished
- sznOfRelease: season of release (Winter, Spring, Fall)
- description: synopsis of plot
- studios: studios responsible for creation
- tags: tags, genres, etc.
- contentWarn: content warning
- watched: number of users that completed it
- watching: number of users that are watching it
- wantWatch: number of users that want to watch it
- dropped: number of users that dropped it before completion
- rating: average user rating

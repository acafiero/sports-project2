# Discovering Valuable Prospects Based on WAR and RAPTOR
### An analysis utilizing metrics to locate ideal NBA candidates

Author: Andrew Cafiero

The franchise has seen a collective downturn of success and is in need of a full rebuild in order to regain parity with the league. The most immeadiate way to address this is to locate and sign quality veteran players.

## Data:
Outsourced from fivethirtyeight which is a site that focuses on analysis of politics econ and sports; this specific dataset consisted of 21 categories and almost 4100 rows of athletes in various seasons. Ours utilizes a handful of metrics but we narrowed it down to possessions, total minutes played, WAR, RAPTOR, Pace Impact, PREDATOR and On/Off score.

## Methods:
Cleaned the data, removed a lot of unncessary features and averaged out all the stats of each player, then removed any prospect that had any negative stats. We created new category called Next WAR representing our prediction of the next season's Wins Above Replacement for each athlete-- this that would help us predict and cluster our potential assets together.

## Results:

### Identifying Current WAR vs Predicted WAR

![image](https://user-images.githubusercontent.com/103779074/188064627-7af84c74-09fb-47a1-a440-ba98acb6f5b0.png)

### Identifying Current RAPTOR vs Predicted WAR
![image](https://user-images.githubusercontent.com/103779074/188064689-3e251d52-5ee2-4b38-85e6-74fe99d02de2.png)


### Identifying Correlation of Predator vs WAR
![image](https://user-images.githubusercontent.com/103779074/188064743-5d28aa1f-b881-4d83-93a3-5dc01b0f65cd.png)


## Model:
Clustering and color coding the athletes into high value (yellow), "average" value (purple), and low value (green), we tilized a Nearest Neighbors to see how our Next WAR data would test. Wanting to further to compare our generated category to a different result we utilized a Decision Tree Regressor and found our data to be 89% accurate.

![Next WAR Model plot](https://user-images.githubusercontent.com/103779074/189432109-4a8ecf62-b0b0-414c-9baa-a812f3acd705.jpg)

## Recommendations and Next Steps
There are high value WAR assets, as high as securing 26 wins on their own, so with this cluster of candidates we can pursue further detailed analytics to decide on what is best for the organization. Our biggest hurdle for the future is the ever-present chance of possibly overvaluing mediocre players and undervaluing players whose intangible qualities are not represented through our data.

# For any additional questions, please contact ajcafiero58@gmail.com

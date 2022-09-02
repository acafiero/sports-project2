# Discovering Valuable Prospects Based on WAR and RAPTOR
### An analysis utilizing metrics to locate ideal NBA candidates

Author: Andrew Cafiero

The franchise has seen a collective downturn of success and is in need of a full rebuild in order to regain parity with the league. The most immeadiate way to address this is to locate and sign quality veteran players.

## Data:
Outsourced from fivethirtyeight; utilizes a handful of metrics but we narrow it down to possessions, total minutes played, WAR, RAPTOR, Pace Impact, PREDATOR and On/Off score

## Methods:
Cleaned the data, removed a lot of unncessary features and averaged out all the stats of each player, then removed any prospect that had any negative stats.

## Results:

### Identifying Current WAR vs Predicted WAR

![image](https://user-images.githubusercontent.com/103779074/188064627-7af84c74-09fb-47a1-a440-ba98acb6f5b0.png)

### Identifying Current RAPTOR vs Predicted WAR
![image](https://user-images.githubusercontent.com/103779074/188064689-3e251d52-5ee2-4b38-85e6-74fe99d02de2.png)


### Identifying Correlation of Predator vs WAR
![image](https://user-images.githubusercontent.com/103779074/188064743-5d28aa1f-b881-4d83-93a3-5dc01b0f65cd.png)


## Model:
Utilized a Nearest Neighbors to see how our Next WAR data would test.
I wanted to compare to a different result so I utilized a Decision Tree Regressor.


## Recommendations and Next Steps
There are high value WAR assets, as high as securing 26 wins on their own, so with this cluster of candidates we can pursue further detailed analytics to decide on what is best for the organization.

# For any additional questions, please contact ajcafiero58@gmail.com

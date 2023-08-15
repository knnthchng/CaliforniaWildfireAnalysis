# Analyzing California Wildfire Severity Through Time
### Golden Jaguar Warriors
Erik Arbelo-Nguyễn, Jake Boden, Kenneth Chang

## Dataset

Wildfire data was posted on Kaggle, and was originally sourced from the United States Forest Service's Fire Program Analysis system. The dataset contains wildfire data from 1992 to 2015 across the entire United States. The dataset originally came in SQLite, and was then converted to CSV format. For our project, we reduced the dataset down only to records for the state of California and removed any redundant columns and entries.

https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires

## Project Thesis
The genesis of our project was to identify if California wildfires have become more severe over time. In addition, we wanted to see what other factors would correlate with or contribute to any observed trends in the data.

## Defining the Analysis
The first thing to do was to define wildfire severity. Are wildfires worse because there were more occurrences or because they burned more acres? On a similar note, is a wildfire more severe simply if it destroys more property? However,the dataset did not provide sufficient data to analyze the latter. Therefore, we decided to define wildfire severity by the acreage burned.

Another interesting piece we wanted to analyze was the human element. Are wildfires caused by mankind worse than those caused by nature? Are wildfires caused by mankind mostly accidental or intentional?

## Analysis
We focused our analysis on 2,000 wildfires across California from 2001 to 2020 which comprised of each year’s 100 most severe wildfires. The analysis consists of two parts: a brief analysis of the acreage burned and then a comparison of fires in Northern California and Southern California.

After reviewing the data, we have determined that fires are getting worse each year overall. Large spikes in average acreage burned each year are preceded by low points in average acreage burned. However, the average acreage burned by wildfires continues to trend upward, with 2020 showing an enormous upward spike. While the average number of acres burned in Southern California seems roughly constant between 2001 and 2020, the average acreage burned in Northern California has risen across the years and the region seems to bear the brunt of the acreage spike of 2020.

![image](https://user-images.githubusercontent.com/120428864/219266046-60c62e3d-d5e5-4218-85c1-9b94c6a8d478.png)

Wildfire causes are grouped into three categories: natural, human, and those which are missing data or have an unspecified or undetermined cause. Additionally, wildfire causes and acreage burned are not distributed evenly across the state. In Southern California, 616 of the total 928 wildfires were attributed to human causes, many of which occur in close proximity to densely and largely populated areas such as the city of Los Angeles, Orange County, the Inland Empire, and San Diego.

![image](https://user-images.githubusercontent.com/120428864/219266080-5dcd69de-0d45-48a4-b894-366f296a3159.png)

Conversely, in Northern California, wildfires are attributed almost evenly to both human and natural causes, with 545 and 401 wildfires respectively. However, naturally-caused wildfires have burned more acres: 5,256,338 acres compared to the 4,008,475 acres burned by human-caused wildfires, which is about 31% more acres burned. Many of the naturally-caused wildfires occur within the national forests, parks, and wilderness areas that predominate the region and are located a fair distance away from major population centers such as the San Francisco Bay Area, Sacramento, and the Central Valley.

![image](https://user-images.githubusercontent.com/120428864/219266351-166a8dc0-7f00-4de2-a37d-0e6fe862ceda.png)

Across both Northern and Southern California, wildfires seemed to form a bell curve across the year, with most of the wildfires occurring between the months of May and October and peaking in July. That trend is observed both with natural and human-caused wildfires. The combination of California's hot and dry summers with increased human activity in natural areas may factor into why the spring and summer months see the most wildfires across the state and across all causes.

![image](https://user-images.githubusercontent.com/120428864/219266564-78754f22-8e8f-474e-86fe-60e962d1c0c4.png)

![image](https://user-images.githubusercontent.com/120428864/219266589-e0d19a68-f1ad-4da0-8bec-5a376616d12a.png)

Looking at the map, human-caused fires occur in closer proximity to major cities and other urban areas, which is most noticeable in the fire map of Southern California. There appears to be a crescent of mostly human-caused wildfires stretching from Santa Barbara and Ventura County, going eastward north of Los Angeles, then crossing south around San Bernardino down to the border. The crescent seems to surround the densely populated areas of Los Angeles, Orange, San Bernardino, Riverside, and San Diego Counties.

The close proximity and easy accessibility of natural areas to Southern California residents may increase the risk of wildfires that can destroy what many residents enjoy regularly. A similar pattern also emerges in Northern California, where human-caused wildfires occur in close proximity to cities and towns, but they are not as numerous as in Southern California. More noticeably, the roughly even ratio between naturally-caused and human-caused wildfires is also visible in the Northern California map, but some naturally-caused fires have burned just as many, if not more, acres than some human-caused fires.

## Conclusion
Surveying the largest wildfires of the past two decades has shown that they are worsening, burning more acres with each year, all across California. Across the state, human activity is predominant in causing wildfires, and is especially prevalent in Southern California. That coincides with the spring and summer months, when recreational human activities such as tourism and camping, as well as agriculture, are at their peak.

For Northern California, naturally-occurring wildfires have burned a sizably larger amount of acres compared to human-caused fires, which can be attributable to the heavily-forested geography of the region. Additionally, the spring and summer months bring hotter and drier weather, which can further sustain wildfires. The challenge of Northern California's naturally-caused wildfires may necessitate changes in forestry practices to prevent them from worsening.

In both cases, the people of California have an integral role to play in preventing the occurrence of and mitigating the destructiveness of wildfires, whether by upholding safe and responsible fire handling practices or advocating for new laws and policies to protect the forests and wildlands they enjoy and depend on. The residents of this state will do well to remember that they can prevent wildfires.
<br></br>
## License

[MIT](https://choosealicense.com/licenses/mit/)

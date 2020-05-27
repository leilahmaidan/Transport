# Trucking Takes The Long Winding Road Downwards 


### Write your nutgraf here

More than half a million jobs in transportation and warehousing were lost in April. The unemployment rate for the sector rose to 13.5% for the same month, according to the Bureau of Labor Statistics. The industry began struggling in February, when factory shutdowns in China caused supply chain backups and eventually a drop in goods moving across the U.S. Then the lockdowns hit North America, causing the industry to take a second hit when businesses shut down and shipping demand dropped even further. 


What else has been done on this topic (provide links)? How is your angle different or fresh?

- [Truckers hit by coronavirus pandemic face rocky road to recovery (Reuters)](https://www.reuters.com/article/us-health-coronavirus-trucking/truckers-hit-by-coronavirus-pandemic-face-rocky-road-to-recovery-idUSKBN22Q1J5)
- [Industries hit hardest by coronavirus in the US include retail, transportation, and travel (USA Today)](https://www.usatoday.com/story/money/2020/03/20/us-industries-being-devastated-by-the-coronavirus-travel-hotels-food/111431804/)
- [How Hard Could Coronavirus Hit Supply Chains? It Depends On What Truckers Decide (WNYC)](https://www.bisnow.com/south-florida/news/economy/truckers-economy-coronavirus-103429)

## Describe how and where you found the data with links to sources. Put the raw data (csv format) in a folder called `data` in this folder. Make a folder called `notebooks` where you will write your pandas code.
 
 Data was found from the Burea of Labor Statistics, CASS Information Systems (An industry leading data analytics provider for freight services), DAT Analytics (An industry leading data analytics provider for freight services), and the U.S. Department of Transportation. 

Write up at least one or up to three findings from your analysis based on the data you found.

- Trcuking spot-rates hit an all time low in April. 
- March saw a sharp spike upwards in spot-rates when shippers were scrambling to find carriers for the rapid shift in demand.
- States such as Nevada Utah and Kansas saw some of the lowest spot rates relative to the nation.
- States such as Washington, DC saw the highest increase in freight charges over a one month period for latest available data, in contrast, Arizona saw the highest decrease for the same perdion. 

## Who are some potential human sources you could reach out to for more info?
Below are all people I spoke to for the artcile:
1. Tali Haleua, founder of Fuelogistics, freight company
2. Mickey Blashfield, president and CEO of the Michigan Trucking Association
3. Garland Hutson, manager at CM Truckbeds, a company that supplies bodies for trucks.
4. A public relations associate at DAT Freight Analytics 

## What is the maximum (best) story possible? What's the minimum (fallback) story if your hypothesis doesn't prove out?

Detailed insight as to why the rates dropped and how the industry will recover would be best possible story. Fall back would be an overall outlook of the trends without being able to back it up woth real people stories. However, I was able to achieve real people insight and insert it into data. 


## How to publish and submit your project

1. Make sure you have navigated to your `data-journalism` folder with your terminal first. Clone a fresh copy of this template and navigate to the folder.

   ```
   git clone git@github.com:JOUR73351/pandas-project.git NAME-OF-YOUR-PROJECT-HERE
   cd NAME-OF-YOUR-PROJECT-HERE
   ```

2) Remove my git tracking from the project

   ```
   rm -rf .git
   ```

3) Create a new repository on GitHub called `NAME-OF-YOUR-PROJECT-HERE` with the following settings.
   <br>
   <img src="assets/newrepo.png" width="500">

4) Run these git commands to initialize the repo. Make sure you've checked `ssh`.

   ```
   git init
   git add -A
   git commit -m "first commit"
   git remote add origin git@github.com:YOUR-USERNAME-HERE/YOUR-REPO-HERE.git
   git push -u origin master
   ```

5) Write your pitch in `README.md`.

6) Write your story in and add your assets and charts to `index.html`. Feel free to play around with and change the styles in `style.css`, but you are not required to. Delete the code that you don't need for your story. The story itself should be no less than 150 words and include at least one chart from Datawrapper. You can embed a Datawrapper chart in your story by copying the embed code into your html as I have done in `index.html.`
   <br>
   <img src="assets/datawrapper.png" width="500">

7) You can preview a local version of your story by running a python server.

   ```
   python -m SimpleHTTPServer 8000
   ```

   Then, navigate to `http://localhost:8000` in your browser. Before step 8, you must quit the python server by pressing `ctrl+c`.

8) To save a version of your story on GitHub, run the following git commands.

   ```
   git add -A
   git commit -m "YOUR-COMMIT-MESSAGE-HERE"
   git push
   ```

9) To publish, go to the settings of your GitHub repo, scroll down to GitHub Pages, and configure the source to the master branch.
   ![GitHub Pages](assets/ghpages.png)

# Tweede Kamer Tweets
A network visualization and analysis on the twitter activity of 'Tweede Kamerleden': members of the Dutch 2nd Chamber of Parliament.

Starting as a small project with the aim to learn webscraping, twitter analysis and network visualization whilst visualizing some interesting information.

![visualize](https://i.imgur.com/f6GiIpW.png)

## Lay-out of the project

The python code is found in Tweede Kamer Anonymised API.ipynb. For interaction with the twitter API private keys are needed, which (obviously) can't be published. All new development is thus first tested on a local directory. All data scraped from twitter can be found in Data/textfiles. Data/csv contains network data and information used in Gephi to visualize the network. Gephi project files and visualized output can be found in Visualizations.

Main dependencies are common packages. The imports are all at the top of the .ipynb file: if they don't run please pip-install required packages.

- Webscraping to get twitter accounts is done using BeautifulSoup, requests and Selenium.
- Twitter information is found using python-twitter
- Data is formatted and analyzed using Pandas and networkx
- Visualized using Gephi

# To-Do
## Urgent
- Code works, but is very messy and needs to be improved to pep-8 standard
- Include multiple forced and unforced network visualizations
- Run network analyses (centrality, betweenness, etc.) and visualize those results

## Future
 - Improve structure of project files if project grows bigger
 - Expand visualisation to not only include Tweede Kamerleden, but also every account encountered during twitter search to visualize possible information-bubbles.

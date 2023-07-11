# GHAS-Settings

This code is written to allow the user to utilize Python libraries Playwirght & BeautifulSoup4 as well as a GitHubs API to get a list of an enterprise 
networks Repository names, dependabot, code scanning, secret scanning, GitHub Advanced Security Settings, and Secret Scanning Push Protection setup.

This code allows users to authenticates into Github utilizing a employee of the enterprises network authentication login information and token keys.
While authenticating into github the code allows you to iterate through each of the https://github.com/orgs/ENTERPRISE/security/coverage pages.
The code uses webscrappping, takes the data gathered and exports to a CSV file. The Github API allows you to get the GitHub Advanced Security Settings and 
Secret Scanning Push Protection setup.

The security coverage page is in Beta so their is no current API that will allow a user to pull all this data down at once.

While working on scrapping data in the HTML there was SVG data within the tree that was unable to load after clicking on {Security Settings} on a repository. 





I was hired as a front-end developer to update existing — and implement new — features for a proprietary timekeeping system. My portion of the application required mainly using Flask(Python) and VueJS. I had little experience using either prior to this project, but was able to quickly learn what was neccessary to deliver on my assignments. 

My first assignment was implementing a print to PDF feature for reporting. As I found out, HTML does not directly translate to PDF. After troubleshooting and researching I found a conversion tool, WeasyPrint, which I was able to import into the project. Using WeasyPrint along with a custom stylesheet, I was able to push the feature and it was moved into production. Having the PDF reports was a big win for the client.

Another requested feature from the client was the ability to add and delete multiple rows of data from an existing tabular report. Using Javascript and Ajax requests, I implemented a feature that allowed a user to select multiple items from a list of paginated data, remove them, and have the table show the updated result. Previously, the user would have to make their changes and refresh the page in order to see the result.

Additional features I implemented were:
* A geolaction feature that checked for location permissions on the user's device, and if permissions were disabled, browser specific instructions were given to enable them.
* Created an accessible version of the site which included removing and altering animations, improving contrast and font sizes, and changing the navigation structure.
* Added additional API endpoints and back-end logic to address the accessible version, and additionally modified existing endpoints to account for updates to features I worked on.

As this is a proprietary software, I do not have access to the code or finished product. However, the owner/project manager that I worked for [left a recommendation for me on LinkedIn praising my work](https://www.linkedin.com/in/chris-pulver/).

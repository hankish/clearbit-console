# Clearbit Console #

This project is a very simple UI wrapper around [Clearbit](https://clearbit.com/)'s API. For now it is only able to use the [Name to Domain API](https://clearbit.com/docs#name-to-domain-api).

What is this useful for? If you have a long list of company names and you want to get their root website domains, this tool will let you paste in the company names and get the web domains. The list returned by the Clearbit API can then be copied to the clipboard or exported to CSV.

This "tool" is just a single html file. The UI is built using [LitElement](https://lit-element.polymer-project.org/) along with some components from Google's [Material Web Components collection](https://github.com/material-components/material-components-web-components).

## How to use the tool ##

- First you'll need to create a free Clearbit account and get an API key
- Then download the `index.html` file from this repo to your computer and open it in a web browser
- Enter in your API key and paste a list of company names, one per line
- Click the "Run Query" button and wait for it to finish
- There will be a table of results with three columns
- You can then either copy the contents of one of the columns to your clipboard or scroll all the way to the bottom and click the "Export to CSV" file
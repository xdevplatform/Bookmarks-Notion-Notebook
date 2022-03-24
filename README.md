# Bookmarks lookup and Notion
We’ve heard that many use their Bookmarks as a to-do list. If you are one of those people, you can build a solution using the API of your favorite project management tools, such as Notion, and then use [Bookmarks lookup](https://developer.twitter.com/en/docs/twitter-api/tweets/bookmarks/) to get a list of Bookmarks to add. This Jupyter Notebook walks you through how to build such a solution.

## Getting set up with the Twitter API
To use this code sample, you will need to [sign up](https://t.co/signup) for a Twitter developer account. Each Project contains an App, with which you can generate the credentials required to use the Twitter API. To use OAuth 2.0 will need to first enable OAuth 2.0 in your App’s auth settings in the Developer Portal to get your Client ID and Secret. You can learn more about getting started with the Twitter API in the getting started section of our documentation. 

## Getting set up with Notion's API
First, you will need to set up an integration directly in your Notion account and share your integration with the database you are looking to update. You can learn more about Notion’s API and how to get started in their [developer documentation](https://developers.notion.com/).

Once you have your Database ID and your API key, you can set up the following environment variables in your terminal.

```
export NOTION_DATABASE_ID='your-database-id'
export NOTION_API_KEY='your-api-key'
```

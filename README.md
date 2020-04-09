# YouTube-Video-Search
Pre-requisites:
1. Install Node
2. Run npm Install
3. Install PostGreSQL
4. Set up the connection with the DB
5. Pick configuration from file be_config.json

Steps to run:
1. Run the command node -r @std/esm
2. open localhost:3000 in the browser

Features:
1. fetches latest videos in sorted order as descending based on published dates
2. paginated response for batch insertion and uniqueness among the records
3. API call to youtube every 10 seconds by the server in the background as an async process
4. facilitates basic search for the videos in DB based on description

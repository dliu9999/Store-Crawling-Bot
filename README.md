# test-scrape-bot

Requirements:
1. HCI installed
2. Postgres set up locally
3. pip install selenium, beautifulsoup4, psycopg2

To use:
1. Clone repo
2. Use a terminal and navigate into the repo
3. $ heroku create
4. $ git push heroku master
5. $ heroku ps:scale web=1
6. $ heroku logs --tail (to see status updates, will print "worked" when finished")
7. $ heroku pg:psql (to query from the database, e.g. SELECT * FROM popular)

![Chart showing Twitter bots with the most followers](https://cdn.glitch.com/eafa115d-c307-4f55-8c74-1140bb1d0ef7%2Fchart-900px.png)

# My Twitter bots

Based on the [Most Popular Twitter Bots](https://glitch.com/edit/#!/twitterbots) project.

# How to use

1. [Create a new Twitter app](https://botwiki.org/resource/tutorial/how-to-create-a-twitter-app/).
2. Add your API keys to `.env`.
3. Create a Twitter list with all your bots.
4. Add your username and your Twitter lists slug to `.env`.
5. Visit your project's page to see the data.


## Technical notes

You can force data reload by setting up the `SYNC_INTERVAL_PASSWORD` inside your `.env` file and then visiting `https://my-twitterbots.glitch.me/sync?password=PasswordStoredInEnvFile`.

## SteemPress - Blockchain Powered Blog

The goal of SteemPress is to provide a standalone blog engine based on the [steem blockchain](https://github.com/steemit/steem).

### Features

- Twig Templating
- Localization Support

### Running steempress development mode via Docker

From the steempress folder, run

```
docker-compose build && docker-compose up
```

**If this is your first time running steempress, you will also need to update it's dependancies.** To do this, while you have the above command running, open a new terminal window and run:

```
docker exec steempress_development_1 composer install -d /var/www/html
```

This will update the composer requirements to run steempress.

CTRL+C breaks the process.

### Future Feature Ideas

- Comments
- Voting
- Authoring Tools
- Fullpage caching

### Try it Out on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

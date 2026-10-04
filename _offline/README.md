# Offline Scripts

This is a set of tools used to backfill the site with event data. Run `npm install`
or `yarn` to install dependencies. Set the Tokyo Meetup group before importing
events:

```sh
export MEETUP_GROUP="your-tokyo-meetup-group"
npm run scrape-events
```

Imported posts are marked with `city: tokyo` and are the only posts shown in
the Tokyo event listings.
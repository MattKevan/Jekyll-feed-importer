# Jekyll feed importer

Ruby script to import items from specified RSS feeds and save them as Jekyll posts/collections. I should probably turn this into a plugin, but for now this works for me.

### Usage

Ensure the feed-normalizer, yaml, to_slug and sanitize gems are installed.

Set ```feed_file``` to the location of your list of RSS feeds to check. This needs to be a YAML file with the following structure:

```
- name: [Site name]
  feed: [Feed URL]
```

Set ```output_location``` to where you want the posts to be saved (without the trailing slash).

Run ```ruby feeds.rb```

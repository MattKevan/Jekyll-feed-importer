# Jekyll feed importer

Imports items from specified RSS feeds and saves them as Jekyll posts/collections.

### Usage

Ensure the feed-normalizer, yaml, to_slug and sanitize gems are installed.

Set ```feed_file``` to the location of your list of RSS feeds to check. This needs to be in YAML format with the key ```feed:``` for the feed URL.

```
- name: [Site name]
  feed: [Feed URL]
```

Set ```output_location``` to where you want the posts to be saved (without the trailing slash).

Run ```ruby feeds.rb```

# StarredReleasesOpml
Creates an OPML file with all the user's starred (from a specific list) repositories' releases feeds.

By default it uses the repo user, and a list called "RSS Releases", but you can change that.

Limitation: it will only return the first 100 repositories in the list, and may fail if you have more than 100 lists.

## How to use
- Fork the repo
- Edit the [action](.github/workflows/rss.yml) with the desired list and/or user (if needed)
- Run the action (either manually or just wait until midnight for it to run automatically)
- Go to the releases tab and get your file

## Improvements
This was made for personal purposes, and I may add or not more things if I need them.

Some possible improvements:
- Allow to generate multiple files for multiple users or lists (should be easy by using a matrix)
- Allow to have any number of repositories and lists (implement pagination with graphql...somehow)

In any case, if you want to suggesst improvements, feel free to do so! I'll try to reply whenever possible.

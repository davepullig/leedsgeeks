Leeds Geeks — A What's On guide for Leeds Geeks, http://leedsgeeks.net.

Nothing fancy, just a list of geek groups and event organisers in the Leeds
area.

If you want to ammend something you have a few options, in order of preference ;)

* Fork this repo, make your changes and send a pull request.
* Create an issue in the github project.
* Send me a message/email.

Most of the time it's just a matter of updating the `Groups` list in
`leedsgeeks.json`.

Each item is a JSON object containing Name, Description, Schedule and Links
attributes, e.g.

```json
{
    "Name": "Geeks Against February",
    "Description": "A groups for geeks who can only handle February every few years.",
    "Schedule": "29th of the every month",
    "Links": [
        {"Label": "Web", "URL": "http://example.com/"},
        {"Label": "Twitter", "URL": "https://twitter.com/FebGeeks", "LinkText": "@FebGeeks"}
    ]
}
```

Only the Name is required. Most things are deliberately left relatively free-form.

The Groups list is kept in alphabetical order so the code doesn't have to worry
about sorting.

Suggestions for additional information to add are welcome, although I will
fight anything that makes it harder to maintain ;).

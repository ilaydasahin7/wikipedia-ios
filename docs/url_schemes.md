# URL schemes

The URL scheme is `wikipedia://`. The following URLs are currently handled:

| Feature            | Format                                   | Example                                  |
| ------------------ | ---------------------------------------- | ---------------------------------------- |
| Article            | wikipedia://[site]/wiki/[page_id]        | wikipedia://en.wikipedia.org/wiki/Red    |
|                    | https://[[site]/wiki/[page_id]           | https://en.wikipedia.org/wiki/Red        |
| Content            | wikipedia://content                      | wikipedia://content/on-this-day/wikipedia.org/en/2024/08/15                                         |
| Explore            | wikipedia://explore                      |                                          |
| History            | wikipedia://history                      |                                          |
| Places             | wikipedia://places[?WMFArticleURL=]      | wikipedia://places/?WMFArticleURL=https://en.wikipedia.org/wiki/Dallas |
| Places (coordinates) | wikipedia://places/?latitude=X&longitude=Y | wikipedia://places/?latitude=52.370216&longitude=4.895168 |
| Saved pages        | wikipedia://saved                        |                                          |

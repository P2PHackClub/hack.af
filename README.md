# p2phack.club-link-shortener

> [P2P Hack Club](https://p2phack.club)’s Airtable-Based Link Shortener, forked from [hack.af](https://github.com/hackclub/hack.af) by [Hack Club](https://hackclub.com/).

## Setup

* Please make a copy of the template Airtable Base: [https://go.mingjie.info/template](https://go.mingjie.info/template)
* Please also grab the Airtable API Key & Base Key from the API documentations. Head [here](https://airtable.com/api) and click on the base you just created to get started.
* Set `AIRTABLE_BASE` to your Base ID, and `AIRTABLE_KEY` to your API Key.
* Set `LOGGING` to `on` if you want to enable logging, `off` if otherwise.
* Set `BOT_LOGGING` to `on` if you want to enable logging for crawlers, `off` if otherwise.
* Set `CACHE_EXPIRATION` to the number of seconds you want the local cache to be valid.

## Using

All links will be routed through a 302 (Temporary Redirect) because you're using Airtable. Simply visit `example.com/slug` to get redirected.

## License

This project is released under [the MIT license](LICENSE).

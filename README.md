# Noetic

This is a tool for searching [ipfs](https://ipfs.io) on ipfs, although it doesn't do that good of a job (yet). It uses [lunr.js](http://lunrjs.com) to perform the search, and the search index is built by scraping results from [searx.netzplielplatz.de](https://searx.netzplielplatz.de) (a public instance of [searx](https://asciimoo.github.io/searx/), which is itself a metasearch engine, aggregating search results from major search providers). As such, the only thing you're searching here are titles, URLs, and text snippets from about 1100 ipfs pages, because that's the information that's able to be scraped from searx, and those are the pages that have been indexed by major search providers. This is an alpha tool, and shouldn't be considered a good way to search ipfs.

Noetic is on ipfs at [/ipfs/QmYo5ZWqNW4ib1Ck4zdm6EKteX3zZWw1j4CVfKtnAzNdvu/](https://ipfs.io/ipfs/QmYo5ZWqNW4ib1Ck4zdm6EKteX3zZWw1j4CVfKtnAzNdvu/); if that's unavailable, you can find it at [natedobbins.net/noetic/-search](https://natedobbins.net/noetic-search/).

The source for the scraper is [here](https://github.com/doesntgolf/noetic-searx-scraper).

## Contributing

The best way to contribute would be to [contribute to lunr.js](https://github.com/olivernn/lunr.js) or to [discuss how to construct a search index on ipfs](https://github.com/ipfs/archives/issues/8).

## License

Noetic is licensed under the [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/).


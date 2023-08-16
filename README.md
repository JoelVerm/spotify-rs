# spotify-rs
spotify-rs is a Rust wrapper for the Spotify API.

Currently, it only supports the following endpoints:

- album
- artist
- audiobook
- category 
- chapter (Note: they return `500 Server error`, which is an issue with the Spotify API)
- episode
- genres
- player

More will be added in the near future. The library is in its infancy and breaking changes will occur. Any feedback is appreciated.

## License
spotify-rs is dual-licensed under [Apache 2.0](https://github.com/Bogpan/spotify-rs/blob/main/LICENSE-APACHE) and [MIT](https://github.com/Bogpan/spotify-rs/blob/main/LICENSE-MIT) terms.

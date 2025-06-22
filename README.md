# Git Maven


## Generate

Install the lates version of [mdbook](https://github.com/rust-lang/mdBook/) and [mdbook-embedify](https://github.com/MR-Addict/mdbook-embedify/) either by visiting those pages and downloading the **Release**-es,
or, if you have Rust on your computer then by running the following commands:

```
cargo install mdbook
cargo install mdbook-embedify
```


Then running the following command will build the book,  and open your default browser to view the results locally.
If you make changes to your files this process will regenerate and reload the book.

```
mdbook serve --open
```


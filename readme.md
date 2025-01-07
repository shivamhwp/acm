# git-acm - git auto-commit-message

_generate meaningful commit messages locally using AI_.

### ❗requirements</u></b>

1. you should have git installed initialised in the repo.
2. stage the changes you want to commit.
3. just run `git-acm` or `git-acm run`.

### how to use

> ensure `rust` is [`installed`](https://doc.rust-lang.org/book/ch01-01-installation.html) on your system and requirements are met.

1. run `cargo install git-acm`.
2. add [gemini-api-key](https://aistudio.google.com/app/apikey).
3. add this ⬇️︎ in your project's `.env` file.

```JSON
   GEMINI_API_KEY="YOUR_API_KEY"
   GEMINI_API_URL="https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent"
```

4. run `git-acm`.

 <br>

# Contributing

### local development setup

> ensure `rust` is installed on your system . go to [`https://doc.rust-lang.org/book/ch01-01-installation.html`](https://doc.rust-lang.org/book/ch01-01-installation.html) for details.

1. ```bash
   git clone https://github.com/shivamhwp/acm.git
   ```

2. get an gemini-api key (currenlty only this supported) [here](https://ai.google.dev/gemini-api/docs/quickstart?lang=rest).
3. create `.env` file at root > set `GEMINI_API_KEY=" " `.
4. ```bash
    cargo build
   ```
5. `cargo run` to get the commit msg in the terminal.
6. start with `main.rs` and break stuff.

<br>

[report 🐞bugs here](https://x.com/shivamhwp)

bhai(s) : [sargam](https://x.com/sargampoudel) (idea) and [smr](https://x.com/smrdotgg) (suggestions).

<br>

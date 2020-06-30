    Copyright (c) 2020-
    Author: Chaitanya Tejaswi (github.com/CRTejaswi)    License: GPL v3.0+

# API
> Personal collection of static APIs. <br>
> Demo available [here](https://crtejaswi.github.io/API).


- [`CV.json`](CV.json) <br>
    Your CV in a JSON file.

- [`logins.json`](logins.json) <br>
    Your login credentials in a JSON file.

- [`latex1.json`](latex1.json) <br>
    Latex equations for basic Science/Math formulae. (Scraped from [equplus.net](https://equplus.net)) <br>

- [`sanskritAlphabet.json`](sanskritAlphabet.json) <br>
    Devanagari & Roman characters for the Sanskrit Alphabet. (Scraped from [Wikipedia](https://en.wikipedia.org/wiki/International_Alphabet_of_Sanskrit_Transliteration)) <br>
    ```powershell
    import-csv .\sanskritAlphabet.csv -delimiter ';' | ConvertTo-Json | out-file -encoding utf8 .\sanskritAlphabet.json
    ```

🚧
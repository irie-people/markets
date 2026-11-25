# Markets

The markets the largest US companies hold, and the boards behind them, as a map to explore: **https://irie-people.github.io/markets/**

Two maps, side by side and tied together. The markets tree runs from verticals to markets to the companies in each, with the share or figure each holds, every number dated and sourced. The boards map holds the boards of the S&P 500 and the 100 largest US companies by revenue, and of the other companies and bodies the markets name where the sources record a board (publishers, nonprofits, a state board of education): each company, its directors, and the people who sit on more than one board. Pick a company in the tree and its board lights up on the map; pick a director and every board they sit on lights up, with their public roles.

The point of the tie: the same few hundred people sit on the boards of the companies that hold the shares, so the map shows which boardrooms touch which markets, and where one person sits on two boards in the same market.

## Where it comes from

- **Boards and roles:** the public data of [LittleSis](https://littlesis.org), a project of the Public Accountability Initiative and the data [theyrule.net](https://theyrule.net) reads; [Wikidata](https://www.wikidata.org)'s board members, chairs and chief executives, with their dates; and the SEC's [insider-transaction data sets](https://www.sec.gov/data-research/sec-markets-data/insider-transactions-data-sets) (Forms 3, 4 and 5) for 2025 Q4 to 2026 Q3, which show who files as a director now. Each company shows when its board was last updated and which sources checked it.
- **Companies:** Wikipedia's lists of the S&P 500 companies and of the largest US companies by revenue.
- **Markets:** each market names its sources (industry trackers, regulators' statistics, company filings, trade press), with the date of each figure and how sure it is.

The data was read on 2026-11-09, and the Education markets on 2026-11-25: who sells the textbooks to US schools, who writes them, who picks them and who sets the standards they are written to.

## The people in it

The page shows people through public records of their public roles, as the sources above hold them: board seats, executive jobs, government posts, education, memberships and ownership stakes; political donations, from the FEC's records as LittleSis holds them, to political recipients only; and ties to other people only where that person holds a public role too, such as a director, an executive or an office holder. Each person links to their LittleSis page and, where Wikidata has one, to Wikipedia. Private relatives and friends, addresses, contact details and birth dates are never kept.

Board lists and donations are only as good as their sources, which match people by name, so a seat can be out of date, or two people with one name can be taken for one. A correction made at the source, on LittleSis or Wikidata, reaches the next build; to report one here, open an issue.

## Terms

The page's code is under the Apache License 2.0 ([LICENSE](LICENSE)). The data in it is under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), as LittleSis's and Wikipedia's are: credit LittleSis (the Public Accountability Initiative), Wikidata and Wikipedia, and share what you make from it under the same licence. Wikidata's own part is CC0, and the SEC's filings are in the public domain.

## In Irie

[Irie](https://github.com/irie-people/irie)'s Markets plugin shows a map like this one in a window beside your sessions, from a folder of yours, and starts sessions there that keep it current: see [Your markets, as a map](https://irie-people.github.io/irie/recipes.html#markets).

The page is one file that loads nothing from elsewhere.

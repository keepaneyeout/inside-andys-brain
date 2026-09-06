# Inside Andy's Brain

Live at [andyburnhamsbrain.com](https://andyburnhamsbrain.com).

A searchable public record of Andy Burnham: every House of Commons speech, question and division vote from his years as MP for Leigh (2001 to 2017), his ministerial speeches, his mayoral statements (2017 to 19 June 2026, when his mayoralty ended), his Commons contributions since returning as MP for Makerfield in June 2026 (including his Hillsborough Law third reading speech of 14 July 2026), curated press records on his Labour leadership campaign and his election as Labour leader on 17 July 2026, his statements and speeches as Prime Minister from 20 July 2026 via gov.uk, full manifestos, Labour conference speeches, committee evidence and full-text extracts of the government reports behind his major campaigns.

15,083 records, 2001 to 2026, public sources only: Hansard via TheyWorkForYou, Public Whip division data, gov.uk and the UK Government Web Archive, Greater Manchester Combined Authority press and governance minutes, the Parliament Committees API, his public Instagram output, and extracted official reports. Every record links to its source. Press records are summary and link only for copyright reasons; Guardian coverage comes through the Guardian's Open Platform API under its terms.

The search runs entirely in your browser. The site is static: the data ships as two fingerprinted SQLite databases split into chunks, `current-<hash>.sqlite.NNN` for records dated from 2026 and `archive-<hash>.sqlite.NNN` for everything earlier, and the page fetches only the few kilobytes each query needs, using sql.js-httpvfs. Only the current database changes from day to day.

Built from a structured public-record vault. Data snapshot: 6 September 2026.

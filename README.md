# Royale Insight

A Clash Royale analytics dashboard with a polished demo mode and optional live player lookup.

## Start

1. Install Node.js 18+.
2. Run `npm install`.
3. Run `npm run dev` and open the URL shown in your terminal.

The dashboard works immediately with **clearly labeled sample data**.

## Enable live player lookup

1. Get a developer API token from https://developer.clashroyale.com/ (IP allowlisting may be required).
2. Copy `.env.example` to `.env` and set `CLASH_ROYALE_API_TOKEN`.
3. In a second terminal run `npm run server` while `npm run dev` continues.
4. Search for a player tag. Real player stats and recent battles will appear. Demo mode is still available.

Do not put the API token in frontend source code or commit `.env`.

## Notes

The official API does not expose full replay actions. Deck analysis here uses transparent heuristic rules, **not** AI or detailed replay analysis. Battle log stats are limited to the matches returned by the API. This project is unofficial and not affiliated with Supercell.

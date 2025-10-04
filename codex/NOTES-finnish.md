# CODEX Yleisesti

## Iso organisaatio vs 1 kehittäjä
On tullut huomattua että monet default käytäntötavat ei sovi ollenkaan 1 kehittäjälle.
Codex täytyy aina käynnistää "codex --dangerously-bypass-approvals-and-sandbox" ja "/new" antaa väärät oletukset.

## Tietokoneen ohjaus
Näköjään uusi codex malli ei suostu "ajamaan tietokonetta".
```
▌   1. gpt-5-codex low
▌   2. gpt-5-codex medium
▌   3. gpt-5-codex high
▌   4. gpt-5 minimal        — fastest responses with limited reasoning; ideal for coding, instructions, or lightweight tasks
▌ > 5. gpt-5 low (current)  — balances speed with some reasoning; useful for straightforward queries and short explanations
▌   6. gpt-5 medium         — default setting; provides a solid balance of reasoning depth and latency for general-purpose tasks
▌   7. gpt-5 high           — maximizes reasoning depth for complex or ambiguous problems
```
Eli kolme ylintä ei suostu esimerkiksi asentamaan Gentoota ssh:n yli.
Tämä on varmaan turvallisuus syistä tai jostain, mutta tällaiset toiminnot on täysin oleellisia, kun yksittäinen kehittäjä yrittää tehdä asioita tehokkaasti.



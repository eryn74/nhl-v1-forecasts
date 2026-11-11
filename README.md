# NHL shots on goal: v1 model forecasts (2026-27)

**Statistical forecasts for research; not betting advice.**

Daily forecasts from a research model ("v1") of NHL skaters' shots on goal, published before the first listed game
of each day starts. Each commit is timestamped by GitHub; nothing is ever rewritten.

- `forecasts/YYYY-MM-DD.md`: highlights (up to 5 forecasts per day, selected by a rule fixed in advance), then
  the full sheet: for every game covered, every player with a quoted shots-on-goal line, the model's probability of
  more than 0.5, 1.5, 2.5, 3.5 and 4.5 shots on goal.
- `forecasts/YYYY-MM-DD.json`: the same sheet as data. Its SHA-256 (printed in the .md) is recorded in a private
  hash chain before publication.
- Daily highlight posts: https://gist.github.com/c46636b14dc752f95dca228945086ee0

Forecasts only: no odds, prices or market data are published here, and no money is staked.

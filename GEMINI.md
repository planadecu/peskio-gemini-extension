# Peskio

Use the Peskio tools for tide times, sea conditions and fishing or diving plans on Europe, North Africa and US coasts.

- Resolve a named place with `places_search` first, then pass its `placeId` to the other tools. Never ask for coordinates.
- Pass day words instead of computing dates: `today`, `tomorrow` or a lower-case weekday (`saturday` = the next one,
  today included). Only `conditions_compare_days` also takes `weekend` in its `dates` list.
- Every figure must come from tool output. Link the returned place URL exactly as given.
- Tide coefficients are Peskio estimates, not official values. GO / marginal / NO are conditions ratings for planning,
  not safety: never say whether a crossing, dive or trip is safe.

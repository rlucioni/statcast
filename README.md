# statcast

Exploration of MLB Statcast data

## Notes

Best public source of Statcast data is [baseballsavant.mlb.com](https://baseballsavant.mlb.com/statcast_search).

### All Players

Need to specify `hfGT=R%7C` (`hfGT=R|`) to limit to regular season games.

```
https://baseballsavant.mlb.com/statcast_search?hfGT=R%7C&season=2017&player_type=pitcher&group_by=name&sort_col=pitches
```

### Player Lookup

Player IDs can be found on the `#player_lookup` element.

```
https://baseballsavant.mlb.com/statcast_search?hfGT=R%7C&player_lookup%5B%5D=518516&season=2017&player_type=pitcher&group_by=name&sort_col=pitches
```

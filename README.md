# Fantasy Football Assistant

A planned personal, noncommercial Yahoo Fantasy Football assistant that would provide read-only advice on start/sit decisions, waiver options, and trades. It would present recommendations for me to review; it would not change my lineup, add or drop players, or submit trades.

## Planned Yahoo data access

If Yahoo API access is approved, the assistant would request only the data needed for those recommendations:

- My roster, including starters and bench players
- My league's scoring settings
- Matchups
- Available players

## Project status

Yahoo API approval is pending. The Yahoo integration has not been implemented, and this repository currently contains only this project description. No Yahoo data is being accessed or stored.

## Privacy

Credentials, access tokens, and private league data must not be committed or published in this public repository. Any future integration should use read-only access where available and keep authentication secrets and personal league data out of version control.

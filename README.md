## The project is at

**https://github.com/PauloRaff/VoteCounter**

but you probably know that already :-)

## Things we need to research
* Google authentication - [quickstart](https://developers.google.com/sheets/quickstart/ios?ver=swift)
* [Interactive Google sheets api documentation](https://developers.google.com/apis-explorer/#p/sheets/v4/)

https://developers.google.com/sheets/quickstart/ios?ver=swift

## Required features
* One vote per person per ballot - multiple voting disallowed.
* Vote should be persisted on device (user would need to delete app and reinstall in order to cheat).
* User can change their vote at any time, so any preexisting vote is undone and the new vote registered.

Two screens:
- a first screen with a list of the ballots
- a second screen showing the choices for the selected ballot and the number of votes each choice has, ranked in order of decreasing popularity.
- The user's current voted-on choice (if any) is displayed selected.
- If the user has not voted yet, none of the rows are displayed selected.
- Until the user votes, we do not display the vote counts accumulated so far

Optional features
 (we also could display the choices in a random order before the user has voted)
 Occasionally poll the server so we get updated results in semi-realtime?

Stretch goals (nice-to-have features)

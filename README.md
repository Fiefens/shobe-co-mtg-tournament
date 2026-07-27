# shobe-co-mtg-tournament
An MTG Tournament Round Constructor and Mentorship-Based Matchmaker

Tournament Organizer - User Guide

1. Add Players

Go to the Players tab.
Type a name and click + Add.
Click the colored dots to set each player's T (Temperament) and S (Skill):
Red = Heated / Beginner
White = Lukewarm / Intermediate
Blue = Cool / Advanced
Click a player's name to rename them, or x to delete.

2. Start a Tournament

Go to the New Tournament tab.
Select Players - check the box next to each player playing.
Format - pick one, or use the recommended (★) format:
Duel - 1v1
Round Robin - everyone plays everyone
Bracket - single loss moves you to the Losers Bracket; lose there and you're out (double elimination)
Swiss - paired by record each round, no eliminations
Matchmaking Mode (4+ players) - Mentorship pairs beginners with players who will be more useful; Competitive is random/standard pairing.
Match Clock - set minutes per round.
Click Start Tournament.

3. Running Rounds

On the round screen:
Use Start / Pause / Reset to run the match clock.
For each pairing, click the winner (or Draw, if allowed).
Click drop to remove a player from the rest of the event.
Once all matches are reported, click Submit Round & Continue.
End Tournament finishes it early and locks in standings as-is.

4. Results & Archive

When the tournament ends, the Results screen shows the champion and final standings.
Click Start New Tournament to begin another.
Click View Archive (or the Archive tab) anytime to see past tournaments - click one to expand full standings.
That's it - add players, start a tournament, report winners each round, repeat.



Beginners get matched to a mentor, not randomly - each Beginner is paired with the best available non-Beginner opponent, using a fixed priority order: Cool+Intermediate first, then Cool+Advanced, then Lukewarm+Intermediate, then Lukewarm+Advanced.
Heated players are last resort mentors - a Heated opponent is only paired with a Beginner if literally nobody calmer is left available that round.
Leftover non-Beginners just get paired off - once all Beginners are matched, any remaining Intermediate/Advanced players are paired against each other with no mentorship logic involved.
This ladder only governs Round 1 - from Round 2 onward (Swiss), pairings shift to being based on standings (best record vs. best record), while still trying to avoid repeat matchups and avoid putting someone against a Heated opponent twice in a row.
Odd numbers produce a bye - if there's one player left over after all the pairing is done, they sit out that round. The bye in later rounds goes to the worst performing player.



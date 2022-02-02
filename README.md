# Paragonladder

A seasonal paragon-ladder for Diablo III hosted at https://ezekiel314.github.io/Paragonladder/. \
All data is received through calls to Blizzards Diablo API.\
The leaderboard is updated via github-workflow on the beginning of every hour.\
Accounts that appeared on any of the leaderboards at one point are candidates for beeing tracked.


## Known Issues
For a reason that im not aware of the `D3 Profile API` returns "Downstream error" for some accounts.\
Whilst the accounts are still tracked, the account information can not be received and they therefore won't appear in the ladder.\
This can exemplary be observed with the battletag `Tok#11317`.

This project was started whilst Diablo III Season 24 was already running, which is why
> Accounts that appeared on any of the leaderboards at one point are candidates for beeing tracked. 

does only apply to accounts that appeared on the leaderboards after the projects start.

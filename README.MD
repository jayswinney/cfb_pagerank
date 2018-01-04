Scroll to the end of the .pynb file to see the ranks.

### Methodology Summary
I applied a version of the google pagerank algorithm to rank college football teams. It's done in two steps, first the ranks are computed where every time a team wins it gets a "link" from the losing team. That system of "links" is used to compute a score for each team. Then I do the opposite in a completely different system, every time a team loses, it gets a "link" from the team it lost to. In the first system teams get a high score for beating teams that have won a lot of games, in the second system teams get a high score for losing to teams that have lost a lot of games. For the final score I subtract the second score from the first so teams are rewarded for good wins and punished for bad losses.

### Caveats / Ideas
It does not account for game score or when/where the games occured. I'll probably explore these features at some point.

see [pagerank wikipedia](https://en.wikipedia.org/wiki/PageRank)

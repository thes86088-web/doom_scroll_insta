# doom_scroll_insta
an agent that does the reels doom-scrolling on the user's behalf.

this agent can :
1. react to the reels sent to your account
  a. adjust the current vector representation of a friend with each reel received
  
2. send reels from your feed into your friends' DMs
   a. maintains datapoint generalization of the set of reels the specified friend sends you
     (each friend is a vector, where basis vectors are emotions)
   
   b. while browsing through your feed :
     i. analyzes the sentiments of the current reel
     ii. sends it to the list of friends with whom dot-product of their average attribute and
         attributes of curent reel is maximum

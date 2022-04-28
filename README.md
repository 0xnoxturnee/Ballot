# B2


Complying with the Remix screenshot requirements, I attached a screenshots subsequently. I accessed contract's giveRightToVote and vote functions via the Remix UI and took the screen captures shown in Figure 2 below

1. The contract was deployed and the giveRightToVote fuction was executed at 10:59am, auto-initializing startTime globally. From line 135 of Ballot.sol; startTime = block.timestamp.


![d2](https://user-images.githubusercontent.com/100279915/165734194-c063fa04-1f1f-468f-abaf-ad98466d7bc4.png)



2. 1 vote was attempted almost 7minutes later. A reverted message was displayed, timestamp included in screenshot. 


![d3](https://user-images.githubusercontent.com/100279915/165734481-c15444a0-b9a4-4903-9120-e45a11685cde.png)

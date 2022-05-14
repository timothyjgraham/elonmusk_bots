# Botometer analysis of Elon Musk's recent followers

I collected data on the most recent 14000 followers of Elon Musk's Twitter account (@elonmusk) and ran the Botometer bot detection model on all accounts that have tweeted at least once (n=4267 accounts).

The results suggest that 8.6% (n=367) accounts are bots. 

I used the Completely Automated Probability (CAP) score, which is defined as the probability, according to the Botometer model, that an account with this score or greater is controlled by software, i.e., is a bot. 

I set a strict threshold of 0.95 to classify an account as a bot. This means that we are willing to accept a false positive rate of 5%, or in other words 19 times out of 20 we will be correct when categorising an account as a bot.

This repository contains a CSV file with the Botometer scores for each of the 4267 accounts under examination.

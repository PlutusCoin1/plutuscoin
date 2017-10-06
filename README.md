PlutusCoin - an educational cryptocurrency based on SmallChange.
In this version there are no direct changes to block targets, etc.
Any changes are left up to the user. SmallChange information can be found below.
I don't take any credit for the SMC source codes, barring the few changes I have made. 
All credit goes to the creator of SMC and Plutuscoin.
You can find a writeup of this project here:
http://www.ocf.berkeley.edu/~baisang/PlutusCoin.pdf
which details the process of using this repository to create your own altcoin,
or simply just understanding how cryptocurrencies work in general.

==================================================================


SmallChange (SMC) - a 'faster' version of Plutuscoin which also uses scrypt
as a proof of work scheme and is intended for microtransactions.
 - 15 seconds block targets: beat that MinCoin! ;)
 - 42 007 680 total coins
 - no subsidy within the first 3 days and after approximately 5 years;
    in between: 4 coins per generated block
 - difficulty retargets every 0.35 days
 - currently peers are looked up over IRC only
 - currently no block checkpoints are in the code (but could be easily
   added)
Other than that, this coin is exactly like Plutuscoin and should by no
means be used as a real cryptocurrency. All of the coin parameters
are chosen arbitrarily or at most with 'fairness' towards everyone in mind.

So actually, this 'new' coin exists for the following reasons:
 - SMC proves that really anyone(!) can start a Plutuscoin/Bitcoin based currency
    (just look at the changes I applied to the original Plutuscoin source,
     for genesis block generation look at main.cpp)
 - allows me to experiment with coin parameters (in a private network)

Finally, I only tested the command line server/tool 'smallchange' for the
first 30 blocks. Credits go to the original authors/communities that
created Bitcoin and Plutuscoin.

Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Plutuscoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.

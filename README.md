# WHIRLPOOL
dApp: https://waves-dapp.com/3PAkmJniMgnnAej5pYf2jFYkCbZow5pt9tr

Reissues WHIRLPOOL for WAVES at price: 1 WAVES + (surplus treasury value / WHIRLPOOL total supply), and price can only increase.
If market price < issue price, then buy from the pool.

Tracks WHIRLPOOL:
- issue price
- value of surplus treasury value
- total WAVES received through issuance
- total WAVES distributed
- ROI

# Bug and hack bounty
dApp: https://waves-dapp.com/3PBbLJcBjLWUZZrFFUk5s53TdTUneHXDc7e

Hack:
If verifier function is incorrect you can hack the 50 WAVES. (bounty doesn't stack with bug bounty below)

Bug:
If function: buyWHIRLPOOLwithWAVES
-allows unlimited issue
-issue below issue price, more then rounding
Then reward up to 50 WAVES.

Any other bug, reward depending on the issue.

Please inform me in Telegram: @blahdieblah

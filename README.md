Custom ruleset for [spamassassin](http://spamassassin.apache.org/).

Please note these rules work for me and are a documentation of how I changed some personalised rules, they may not suit your environment and create false positives - so please ensure you test these rules in your environment before putting them in production.

Rules Inspired by [KAM's Work on KAM.CF](https://mcgrail.com/template/leadership#KAM)
Some inputs and Learnings from [ERCPE](https://github.com/ercpe/ercpe-sa-rules/blob/master/ercpe-rules.cf) and [JULT](https://gist.github.com/jult/9bfdc4d07b44be01a02cc2aaf25b7c39)

Split into 6 Lists

1. TBG.cf has some old rules
2. TBG_BODY.cf are Body Checks
3. TBG_SENDERS.cf are senders that are known to send SPAM
4. TBG_HEADERS.cf are spammy subjects and headers for detectin
5. TBG_URI.CF URI - URL's that are known to be spammy
6. nonTBGrules.cf - We had some false positives on a few rules, so using them here and also adapting rules from others


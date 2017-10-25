Eliza Polyglot
==============

ELIZA is an early "chatbot", first implemented in the late 60s by Joseph Weizenbaum. ELIZA is, fundamentally, a pattern matching program that tries to emulate the responses of a non-directional psychotherapist (maybe a Rogerian one) in an initial psychiatric interview. In this implementation I've added an extra bit: in any stage of the conversation you can change to other languages and ELIZA will pace with you.

![animation](img/animation.gif)

Notes:

There are dozens of Eliza implementations. 
This one relies heavily in this code: <https://www.smallsurething.com/implementing-the-famous-eliza-chatbot-in-python/>
I have added detection and language translation using TextBlob <https://textblob.readthedocs.io/en/dev/index.html> and Google Translate.





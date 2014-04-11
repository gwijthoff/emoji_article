**roughly 2000 words!**

0. What's an emoji?

- should we start with the stuff on #emojiethnicityupdate? I feel like that's a great hook for their blog format

1.  What is unicode, what is it trying to do, what is it used for

the distinction between syntax and semantics in emoji encoding, and how it relates to the diversity controversy.  Also, how practices respond to standards.

- Japanese core set
- how font maps a code point to a glyph
- unicode's semantic agnosticism
- users vs. standards

2. how is unicode/emoji library codecs used or expressed? (looks like you were starting this stuff in your "convergence" section)  (AMELIA)

- people
- platforms
- systems

3. how are emoji language, objects, things > what do emoji tell us about how people have always communicated with things and systems.  Connection between language and objects, material origins of writing.

- examples of ancient token systems, characters that Unicode can't about (Indonesian example)
- transition into new ways that people communicate through mobile devices -- "fingered speech," such a great phrase

4.  blank texts

* * * * * * * * * * * 

background:
    mobile devices are now our primary means of computing
    the past ten years have entirely changed how we communicate

What does the GUI mean in this story?

how do linguists account for emojis and text speak?
    textured speech
    fingered speech
    reintroducing aural/oral language.  but emojis are pictographic
    this is a stylistic shift (in terms of personal style, fashion) rather than slang

Rich Ling: the "constant touch of carrying a phone and being connected to your network"

the invention of writing lies with the exchange of objects, tokens

emojis are encoded in unicode, with an ISO standard.  but unicode wasn't used in text messaging for a long time.  Once unicode comes into play, the possibilities are endless

*Information Worlds* book -- on bone notches and counting

* * * * * * * * * * * * 

Bytes have room for eight bits.  "Some people are under the misconception that Unicode is simply a 16-bit code where each character takes 16 bits and therefore there are 65,536 possible characters. This is not, actually, correct. It is the single most common myth about Unicode, so if you thought that, don't feel bad."

"But still, most people just pretended that a byte was a character and a character was 8 bits and as long as you never moved a string from one computer to another, or spoke more than one language, it would sort of always work. But of course, as soon as the Internet happened, it became quite commonplace to move strings from one computer to another, and the whole mess came tumbling down. Luckily, Unicode had been invented."

"we had a code for them called ASCII which was able to represent every character using a number between 32 and 127. Space was 32, the letter "A" was 65, etc. This could conveniently be stored in 7 bits. Most computers in those days were using 8-bit bytes, so not only could you store every possible ASCII character, but you had a whole bit to spare, which, if you were wicked, you could use for your own devious purposes"

"Codes below 32 were called unprintable and were used for control characters, like 7 which made your computer beep and 12 which caused the current page of paper to go flying out of the printer and a new one to be fed in."

"UTF-8 was another system for storing your string of Unicode code points, those magic U+ numbers, in memory using 8 bit bytes. In UTF-8, every code point from 0-127 is stored in a single byte. Only code points 128 and above are stored using 2, 3, in fact, up to 6 bytes."
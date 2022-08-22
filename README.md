red-squiggly-braces is a Microsoft Word proofing dictionary of English programming, software design, and computer science terms. Add it to Word's proofing options and it'll get rid of red squiggly lines on words like "iterable", "backport", and "xyzzy."

How do I use it?
---

*Word (as of May 2020)* - File, Options, Proofing, Custom Dictionaries, Add, browse to red-squiggly-braces.dic.

*Word for Mac (as of Aug 2022)* - Word, Preferences, Spelling and Grammar, Dictionaries, Add, and browse to red-squiggly-braces.dic.

*Word Web App* - Unfortunately Word custom dictionaries don't sync to the web app. When they do I'll update this. I suspect Windows 8's spellcheck is based on Office's, so perhaps there's something that can be done with that.

How can I add words to the dictionary locally?
---

Word's .dic files are  UTF-16 LE w/ BOM. Newlines delimit the words. Add words to the file using any text editor, taking care not to break the encoding (Word for Windows appears to be sensitive to it, while Word for Mac is not.)

Or: the Custom Dictionaries screen allows you to view and edit the file.

Or: in Custom Dictionaries if you set the file as the default, when you use the "Add to Dictionary" option in a document, it'll append to the file.

Contributing words
---

Please send a pull request, or open an issue, to suggest to add terms you've seen Word indicate as misspelled.

Please include a reference that shows the term in use. StackOverflow posts that show the term in conversation are great. So are Wikipedia articles.

Please don't suggest trademarks and product names: Word's checker lets proper nouns slide, so it's not that useful anyway, nevermind this project could never hope to keep up on those!

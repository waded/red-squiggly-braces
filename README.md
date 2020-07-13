red-squiggly-braces is a Microsoft Word proofing dictionary of English programming, software design, and computer science terms. Add it to Word's proofing options and it'll get rid of red squiggly lines on words like "iterable", "backport", and "xyzzy."

Please send a pull request, or open an issue, to suggest to add terms you've seen Word indicate as misspelled.

Please include a reference that shows the term in use. StackOverflow posts that show the term in conversation are great references, and so are Wikipedia articles. Word's checker lets proper nouns slide, so please don't bother suggesting trademarks and product names.

How do I use it?
---

*Word (latest version as of May 2020)* - File, Options, Proofing, Custom Dictionaries, Add, browse to red-squiggly-braces.dic.

*Word 2013* - File, Options, Proofing, Custom Dictionaries, Add, browse to red-squiggly-braces.dic.

*Word Web App* - Unfortunately Word custom dictionaries don't sync to the web app. When they do I'll update this. I suspect Windows 8's spellcheck is based on Office's, so perhaps there's something that can be done with that.

*Word for Mac 2011* - Word, Preferences, Spelling and Grammar, Dictionaries, Add, and browse to red-squiggly-braces.dic.

How can I add to it?
---

Word's .dic files are  UTF-16 LE w/ BOM. Newlines delimit the words. Add words to the file using any text editor, taking care not to break the encoding (Word for Windows appears to be sensitive to it, while Word for Mac is not.) Or: the Custom Dictionaries screen allows you to view and edit the file. Or: in Custom Dictionaries if you set the file as the default, when you use the "Add to Dictionary" option in a document it'll append to the file.

# anki_tex
A workaround to provide support for LaTeX in VScodeAnki -> make flashcard decks with equations in them

This is really just a single script for translating LaTeX for markdown to LaTeX for Anki.

If a line of text contains $E=mc^2$ or $$E=h \nu$$ then it will be turned into [$]E=mc^2[\$] or [$]E=h \nu[\$]. It can be required that the leading '$' has a leading space and no trailing space and that the trailing '$' has a trailing space and no leading space.

This script is using python because that is what I know. It's really just experimentation with regex.

I would prefer to integrate this immediately into VScodeAnki, but I've only breifly looked under the hood of vscode extensions and prefer to work on one problem at a time.

A smooth transition back and forth between Anki and Markdown could be a gamechanger for the study of undergraduate physics, so that is the endgame.

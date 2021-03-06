# east-central-european-dicts

Dictionaries for Eastern and Central European languages:

* Albanian
* Armenian
* Belarusian
* Croatian
* Finnish
* Hungarian
* Latvian
* Lithuanian
* Macedonian
* Polish
* Romanian
* Russian
* Serbian
* Slovak
* Slovenian
* Swedish
* Turkish
* Ukrainian
* Uzbek

They were created for a previous version of my language software I have been working on. All are pre-rendered to HTML in the following format (one JSON entry per line):

> {"title": "...", "titlehtml": "...", "sourcehtml": "...", "contenthtml": "..."}

The dictionary are from freely available sources: Wiktionary, global WordNets, the Unicode CLDR among others.

It also includes automatic machine-generated translations created by Facebook's FastText. Because they have not been checked by humans and generated by statistical methods in bilingual texts, they contain many errors, and so should only be used as a starting point for further investigation.

The hyperlinks were generated with the intention of being used internally by the application, and need to be rewritten based on how they will be used in other apps.

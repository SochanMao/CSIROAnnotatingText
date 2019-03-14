# CSIROAnnotatingText
Annotating text using online vocabularies

Technical documents use terminology with the intention that specific words and phrases denote more or less precise
definitions of some concept. However, in many (most) cases a term has more than one definition in different
vocabularies, which can differ either a little or a lot. Accurate understanding of a text can be enabled by hyperlinking all
technical terms to the intended definitions.
This project will develop a tool and web micro-service to enable semi-automated annotation of a text with hyperlinks to
the definitions of terminology used. The definitions should in turn be sourced from a range of vocabularies (i.e. sources of
terms), accessed through ‘standard’ APIs.
* detect words or phrases within a text that have definitions in one or more source vocabularies
* allow the user to select which definition applies to the usage of the term in the context
* allow the user to select an alternative or preferred term to replace the original
* insert a hyperlink to the definition
* (stretch goal) enable correction of, or addition of a definition for a term or phrase to a public vocabulary service

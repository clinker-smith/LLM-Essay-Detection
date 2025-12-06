# Feature Brainstorming

## Formulaic phrasing

Formulaic, transitional phrasing is often indicative of Gen AI writing ([source](https://www.insidehighered.com/opinion/career-advice/teaching/2024/07/02/ways-distinguish-ai-composed-essays-human-composed-ones)). Examples include

* “Firstly, Secondly, Thirdly, Lastly”
* “In contrast”
* “Furthermore”
* “On the other hand”
* “In conclusion”
* "Moreover"

#### Variable name: 
`n_transition_words`
* Numeric count
#### Variable inputs
`input_transition = ["first", "firstly", "second", "secondly", "third", "thirdly", "meanwhile", "previously", "subsequently", "eventually", "finally", "lastly", "ultimately", "conclusion", "addition", "additionally", "furthermore", "moreover", "besides", "equally", "however", "contrary", "conversely", "despite", "contrast", "nevertheless", "nonetheless", "whereas", "while", "although", "though", "therefore", "thus", "hence", "consequently", "accordingly", "namely", "specifically", "indeed", "importantly", "significantly", "especially", "notably", "undoubtedly", "likewise", "similarly", "correspondingly", "sum", "summary", "overall", "conclude", "conclusion", "simultaneously", "formerly", "lately", "recently", "opposite", "adjacent", "provided", "admittedly", "regarding"]`

## Hyperbolic phrasing

Overreaching descriptive language is characteristic of AI ([source](https://www.insidehighered.com/opinion/career-advice/teaching/2024/07/02/ways-distinguish-ai-composed-essays-human-composed-ones)).
* "powerful"
* “groundbreaking”
* “vital”
* “invaluable”
* “indelible”
* “essential”
* “poignant”
* “profound”

Similarly, excessive exclamation points may be apparent when an LLM is asked to present a first-person, reflective, or passionate assignment.

#### Variable names: 
`n_hyperbole`

`n_exclamations`
* Numeric count

#### Variable inputs:
`input_hyperbole = ["powerful", "groundbreaking", "illuminating", "vital", "invaluable", "indelible", "essential", "poignant", "profound", "remarkable", "transformative", "revolutionary", "unparalleled", "extraordinary", "compelling", "significant", "exceptional", "crucial", "monumental", "dramatic", "robust", "innovative", "pivotal", "impressive", "astonishing", "visionary", "inspiring", "striking", "dynamic", "iconic", "seminal", "trailblazing", "revolutionary", "extreme", "shocking"]`

## Abnormal symbols

Writing submitted by Gen AI may include abnormal symbols such as:
* Brackets: "[]"
* Underscores: "_"
* Asterisks: "*"
* Chevrons: "<>"
* Curly brackets: "{}"

#### Variable name: 
`n_abn_symbols`
* Numeric count

#### Variable inputs:
`input_abn_symbols = ["[", "]", "_", "*", "<", ">", "{", "}", "^", "@", "#", "|", "\")`

## Counterargumentative 

We identified that counterargumentation is a common feature of AI writing. Examples include
* "Not just"
* "Just?"

## Address to the reader

Students lazily using Gen AI will often leave parts of the conversation in the text. Example:

* "Here is your essay:"
* "Here is"
* "Here's"
* "Sure!"
* "Sure"

#### Variable name: 
`prompt_lang`
* Binary (was it present or not)

#### Variable inputs:
`input_prompt_lang = ["here you go", "as an ai", "as a language model", "i generated", "here's the essay", "here's your essay", "let me", "help you", "sure,", "i hope this helps", “your prompt”, “your request”, "here is", "here's", "sure!", "here is the essay", "here is your essay", "language model", "large language", "ai", "generative ai", "chatbot", "your essay"]`

## Em dash count
Chat GPT is often credited with overusing em dashes in its writing:
* "-"
* "--"
* "—"

#### Variable name: 
`n_em_dash`
* Numeric count

## Spelling errors
Find Python package that has a spell check built in. Human writing will have spelling errors.
* SpellChecker

## Anything that has you/your in parentheses or brackets

## Telling, not showing
* In this essay, I will... = AI

## Using words to try to sound human
* Like
* Whatever
* Hey/hello/hi
* Um/Umm

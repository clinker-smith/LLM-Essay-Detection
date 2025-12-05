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

## Counterargumentative 

We identified that counterargumentation is a common feature of AI writing. Examples include
* "Not just"
* "Just?"

## Address to the reader

Students lazily using Gen AI will often leave parts of the conversation in the text. Example:

* "Here is your essay:"
* "Here is"
* "Sure!"

#### Variable name: 
`prompt_lang`
* Binary (was it present or not)

  



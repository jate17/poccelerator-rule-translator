# poccelerator-rule-translator
ASTM rule engine debugger for POCcelerator middleware — paste .ini mapping rules and an ASTM message to get field-level explanations and live transformation output.

Direct Link: (POCcelerator Rule Translator)[https://jate17.github.io/poccelerator-rule-translator/]


POCcelerator uses a proprietary DSL inside .ini files to define how incoming ASTM E1394 messages are transformed before reaching the middleware. These rules are compact and undocumented — reading them without context is non-trivial.
This tool lets you paste a rule block and a raw ASTM message and instantly see what each rule does, which fields get modified, and what the output message looks like after transformation.

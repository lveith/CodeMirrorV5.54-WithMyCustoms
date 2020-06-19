# CodeMirrorV5.54-WithMyCustoms
 Codemirror 5.54 with addional some of my little customs/preparings to use in 4D

### 4D mode is defined in mode/4d.js
- cmds and constants are defined only **static for 4Dv18R3** (please made your own version dynamic if needed)
- method names has only one fix method-name-example (please fill in your own method-names if needed)

All this keywords cmds/constants/methods/...
can filled in dynamically with 4D command
- "PROCESS 4D TAGS"
or with any of this 4D WA commands:
- "WA EXECUTE JAVASCRIPT FUNCTION"
- "WA Evaluate JavaScript"
to set a js-var inside the webarea with your own keywords
and any 4Dversion keywords of currentVersion or virtualStruct from another 4dversion:

### 4D theme is defined in theme/4d.css

Better to use 4Dmode and 4Dtheme together.
You can test other themes too (99% ok),
but there are one or two special-css-selectors
optimized espacially for 4d only in 4d.css.


# TODO list

## Functionality

* conversion from FSM to regex
* regex minimization
* add Moore and Mealy machine support + minimization and Moore<->Mealy transformation functions
* add push-down automata support + transformation to CFG functions
* grammar-related functions: 
  * printHtml
  * isRegular (not possible in general, http://members.fortunecity.com/boroday/Automatatools.html)
  * removeDeadSymbols 
  * removeUnreachableSymbols
  * removeUselessSymbols
  * removeEpsilonProductions
  * removeUnitProductions
  * chomskyForm 
  * greibachForm
  * tofsm 
  * llgToRlg 
  * rlgToLlg 
  * isAmbiguous (not possible in general)
  * reverse
  * isGenerativeTreeValidForGrammar
  * topda
  * generativeTree for string
  * union
  * concatenation
  * kleene
  * parseBnf
  * parseAbnf
  * parseEbnf

## Refactoring and documentation

* unify printAscii and printHtml tables
* add more structured comments to functions (jsdoc?)
* write API documentation for current code
* write overview/list of implemented functionality
* add similar and related projects list: 
  * https://github.com/jakesgordon/javascript-state-machine/
  * https://github.com/fschaefer/Stately.js
  * https://github.com/mdaines/grammophone
  * http://smlweb.cpsc.ucalgary.ca/
* move noam source to /src and webapps to /webapps

## Performance and testing

* refactor internal code to use more optimized data structures
* add performance testing

## Webapps and examples

* develop playground webapp for working with FSMs and grammars
  * defining languages
  * minimizing/transforming languages
  * composing languages
  * editing + instant refresh capability
  * console-based
* playground app
  * stretch UI over whole window (remove fuzzy border)
  * put graph rendering into background worker + re-render only when typing stops for 1-2s
  * image export for graphs
  * develop simple language for defining FSMs
* develop webapp for step-by-step simulation of the operation of FSMs and grammars
* develop examples for FSMs, grammars and regular expressions
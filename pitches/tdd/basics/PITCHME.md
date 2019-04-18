<style type="text/css" >

.fuu {
    color: orange;
}

</style>

# TDD
@fa[vial]

@css[fuu](TEST)

+++

# TDD
### C'est quoi ?
@snap[fragment text-orange]
# Selon vous ?
@snapend

+++

@snap[fragment west span-30]
<h3 style="color: #dd0000">RED</h3>
**Make it fail**
<br>
_
@size[0.7em](No code without a failing test)
_
@snapend

@snap[fragment midpoint span-30]
<h3 style="color: #00aa00">GREEN</h3>
**Make it work**
<br>
_
@size[0.7em](A simply as possible)
_
@snapend

@snap[fragment east span-30]
<h3 style="color: #0000dd">REFACTOR</h3>
**Make it better**
<br>
_
@size[0.7em](Refactor)
_
@snapend

@snap[top]
# The Mantra
@snapend

+++?image=https://blog.myagilepartner.fr/wp-content/uploads/2017/01/tdd.jpg&size=contain

@snap[top]
# The Mantra
@snapend

+++

@snap[west span-30]
## Trois Règles
@snapend

@snap[east span-70]
@ul[split-screen-list list-content-concise text-08](false)
- @size[0.85em](Il est interdit d'écrire du code de production, tant qu'il n'y a pas au moins un test qui échoue)
- @size[0.85em](Il est interdit d'écrire plus d'un test unitaire qui échoue.<br>Les erreurs de compilation sont des échecs.)
- @size[0.85em](Il est interdit d'écrire davantage code de production qu'il n'est nécessaire pour faire passer un test en échec.) 
@snapend

+++

## FACILE! :)

Note:
 - Si vous suivez ces principes et ce cycle, vous ferez du TDD théoriquement.
   Il y a de grande chance que vous n’y arriviez pas, que vous n’aboutissiez pas à du code
   propre, ou que ce soit beaucoup trop difficile…
   
+++

## Euh...

+++

## En vrai...

+++

## Le TDD est DIFFICILE
@snap[fragment ]
## ...et demande
@snapend

@snap[fragment south-west span-30]
Entrainement !
@snapend
@snap[fragment south span-30]
Entrainement !
@snapend
@snap[fragment south-east span-30]
Entrainement !
@snapend

+++

@snap[west span-50]
# En pratique
@snapend

@snap[east span-50]
@ul[split-screen-list list-content-concise text-08](false)
- Très peu de gens utilisent le TDD
- Beaucoup l'abandonnent
@olend
@snapend

+++

### Etape manquante ?
@snap[fragment]
## Par où commencer ?
@snapend

+++

> “You can test all you want and if you don’t
know how to approach the problem,
you’re not going to get a solution”

> **Peter Norvig - “Coders At Work”**

+++

<div style="display: flex">

@snap[fragment]
# Overview (flex)
Analyse Problem
Test List
Guiding Test
@snapend

@snap[west span-30]
<h3 style="color: #dd0000">RED</h3>

@snap[fragment]
@ul
- Declare & Name
- Arrange-Act-Assert
@ulend
@snapend

@snapend

@snap[midpoint span-30]
<h3 style="color: #00aa00">GREEN</h3>

@snap[fragment]
@ul
- Implement solution
- Fake it
- Start over
@ulend
@snapend

@snapend

@snap[east span-30]
<h3 style="color: #0000dd">REFACTOR</h3>

@snap[fragment]
@ul
- Remove Fake
- Remove Code Smell
- Improve Design
- (No new functionality)
@ulend
@snapend

@snapend

@snap[fragment]
# Think
@snapend

</div>

Note:
- Writing a failing test tells you:
  - what problem you are solving
  - if your design is inconvenient  
- Getting to Green:
  - makes you write only just enough functionality
  - Avoid over design & code bloat
  
+++

@snap[north]
TDD is dead. Long live testing.
By David Heinemeier Hansson on April 23, 2014
http://david.heinemeierhansson.com/2014/tdd-is-dead-long-live-testing.html
@snapend

@snap[south]
A series of conversations between Kent Beck, David
Heinemeier Hansson, and Martin Fowler on the topic of
Test-Driven Development (TDD) and its impact upon
software design.
From may to june 2014
http://martinfowler.com/articles/is-tdd-dead/
@snapend

+++

# Aller plus loin
### TODO: slide mal placé

+++


@snap[north]
### Inside-Out
#### (Classic school, bottom-up)
@snapend

# vs.

@snap[south]
### Outside-In
#### (London school, top-down or "mockist TDD")
@snapend

+++

Liens

@ul
* https://fr.slideshare.net/brunoboucard/si-le-tdd-est-mort-alors-mix-it
* http://david.heinemeierhansson.com/2014/tdd-is-dead-long-live-testing.html
* http://martinfowler.com/articles/is-tdd-dead/
* http://codurance.com/2015/05/12/does-tdd-lead-to-good-design/
* http://www.jamesshore.com/Blog/How-Does-TDD-Affect-Design.html
@ulend
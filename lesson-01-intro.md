# cycle de vie du logiciel #

## description ##

## implimentation ##
- coudage / programmation
- test
- Intégration
- analyse
- concéption

```mermaid
flowchart LR
A(analyse)
C(concéption)
D(codage)
T(test)
I(intégration)

 A-->C
 C-->D
 D-->T
 ```
 
 ## SOURCE CONTROL ##
 La gestion du code source
 on utilise git, il y ad'autres systemes

 le flux quand on developpe
 ```mermaid
 flowchart
 C(code)
 R(local repository)
 G(github)
 C --commit--> R
 R --push--> G

 ```
 
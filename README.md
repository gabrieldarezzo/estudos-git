# Estudos sobre o Git


## O que é git  
O Git é um sistema de controle de revisão distribuído rápido, escalável e com um conjunto de comandos extraordinariamente ricos que fornecem operações de alto nível e acesso total aos internos.


## Entender o conceito do git  
Sistema de controle de revisão distribuído
 
## Diferenças entre Git e SVN  


## O que é o git-flow  
Criado pelo Vincent Driessen,

É um fluxo de trabalho, adotando nomenclaturas:  
`hotfixes`, `release-branches`, `develop`, `feature-branches`.


![Git Flow](docs/git-flow.jpeg)  


### Workflow :


#### 1:branch = 1:feature 

Cada alteração é feita via branch, seja HotFix/BugFix, novas funcionalides, ou até mesmo versões novas (diversas funcionalidades) tentando sempre manter a `master` atualizada e mantendo ciclos de deploy constante.  

**Prós:** Simples, Controle  
**Problemas:** Equipes muito grandes podem gerar conflitos na master, e descobrir que o merge não estão tão certo assim (e já está na master)   
![Hehe](docs/hehe.jpeg)  


#### GitHub-Flow
Uma versão sem simplificada do Git-Flow, onde possui um bugfix 


**Prós:** Simples, Controle  
**Problemas:** Equipes muito grandes podem gerar conflitos na master, e descobrir que o merge não estão tão certo assim (e já está na master)   
![Hehe](docs/hehe.jpeg)  








## Referência

Entendendo GIT | (não é um tutorial!):  
https://www.youtube.com/watch?v=6Czd1Yetaac  

Git - git flow na prática:  
https://www.youtube.com/watch?v=wzxBR4pOTTs  

https://semver.org/  

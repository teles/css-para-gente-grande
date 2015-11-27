# CSS para gente grande

## Tópicos

### Diretórios e arquivos

- [ ] O que tem no diretório base/?
- [ ] O que tem no diretório base/properties/?
- [ ] O que tem no diretório base/utilities/?
- [ ] O que tem no diretório helpers/?
- [ ] O que tem no diretório helpers/functions/?
- [ ] O que tem no diretório helpers/mixin/s?
- [ ] O que tem no diretório helpers/variables/?
- [ ] O que tem no diretório modules/?
- [ ] O que tem no diretório module/module-1/?
- [ ] O que tem no arquivo-principal?
 
### Boas práticas
- [ ] - Declares seus imports em um único arquivo.
- [ ] - Não tenha media-queries em arquivos separados.
- [ ] - Defina seus breakpoints como variáveis.
- [ ] - Tenha uma paleta de cores.
- [ ] - Defina cores por contexto baseado na sua paleta.
- [ ] - Crie um sistema de iconfont baseado em glifos.
- [ ] - Padronize seus espaçamentos
- [ ] - Documente seu css

## Nomenclatura
- [ ] - Nomenclatura para componentes, classes aninhadas, estados, e variações.

## Zen do css
- [ ] - Explícito é melhor que implícito
- [ ] - Nomeei pelo contexto não pela aparência
- [ ] - Escreva primeiro para mobile
- [ ] - Renderize primeiro para mobile

## Arquitetura de diretórios para projetos css

A estrutura de um projeto css pode ser definida a partir da estrutura de diretórios e arquivos. A seguir um exemplo de estrutura de arquivos que segue o css-styleguide:

    ├── base/
    │   ├──icon-font
    │   ├──reset
    │   ├──typography
    │   └── properties/
    │   │   ├──float
    │   │   ├──spacing
    │   │   ├──other-property-1
    │   │   ├──other-property-2        
    │   │   └──other-property-n            
    │   └── utilities/
    │       ├──utility-1
    │       ├──utility-2
    │       └──utility-n    
    ├── helpers/
    │   ├── functions
    │   │   └──spacing
    │   ├── mixins/
    │   │   ├──mixin-1
    │   │   ├──mixin-2
    │   │   ├──mixin-n
    │   └── variables/
    │       ├──icon-font
    │       ├──grid
    │       ├──pallete
    │       ├──spacing
    │       └──typography
    └── modules/
    │    ├──module-1/
    │    │   ├──module-1
    │    │   ├──module-1-state    
    │    │   └──module-1-doc    
    │    ├──module-2
    │    └──module-n    
    └─ arquivo-principal

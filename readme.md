# CSS para gente grande

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

# CSS styleguide

## Arquitetura de diretórios para projetos css

A estrutura de um projeto css pode ser definida a partir da estrutura de diretórios e arquivos. A seguir um exemplo de estrutura de arquivos que segue o css-styleguide:

    ├── base
    │   ├──icon-font.css
    │   ├──reset.css
    │   ├──typography.css
    │   └── properties
    │   │   ├──float.css
    │   │   ├──spacing.css
    │   │   ├──other-property-1.css
    │   │   ├──other-property-2.css        
    │   │   └──other-property-n.css            
    │   └── utilities
    │       ├──utility-1.css
    │       ├──utility-2.css
    │       └──utility-n.css    
    ├── helpers
    │   ├── functions
    │   │   └──spacing.css
    │   ├── mixins
    │   │   ├──mixin-1.css
    │   │   ├──mixin-2.css
    │   │   ├──mixin-n.css
    │   └── variables
    │       ├──icon-font.css
    │       ├──grid.css
    │       ├──pallete.css
    │       ├──spacing.css
    │       └──typography.css
    └── modules
    │    ├──module-1
    │    │   ├──module-1.css
    │    │   ├──module-1-state.css    
    │    │   └──module-1-doc.html    
    │    ├──module-2.css
    │    └──module-n.css    
    └─ arquivo-principal.css

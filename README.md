<img src="https://img.shields.io/badge/Abrangência-Coordenação-008290?style=for-the-badge" alt="Abrangência: Coordenação"/>
<img src="https://img.shields.io/badge/Processo-Geral-008290?style=for-the-badge" alt="Processo: Geral"/>
<img src="https://img.shields.io/badge/Ambiente-DEV-6c757d?style=for-the-badge" alt="Ambiente: DEV"/>
<img src="https://img.shields.io/badge/Status-Validação-1565c0?style=for-the-badge" alt="Status: Validação"/>
<img src="https://img.shields.io/badge/Tipo-Script_utilitário-6c757d?style=for-the-badge" alt="Tipo: Script utilitário"/>
# imagens_vale — acervo visual

imagens_vale — acervo visual.

## Arquitetura

```mermaid
flowchart LR
  subgraph internet ["INTERNET"]
    direction TB
    subgraph saas ["SaaS Microsoft 365"]
      ADO["Azure DevOps"]
    end
  end

  subgraph it ["IT ValeNet"]
    direction TB
      RAW["Acervo"]
      CAT["Índice"]
      USE["Consumo"]
  end

  RAW --> CAT
  CAT --> USE

  classDef zonaIT fill:#0d3d38,stroke:#2ec4b6,color:#d4f5f0
  classDef zonaInternet fill:#3a1520,stroke:#e85d4c,color:#ffd4ce
  classDef z fill:#1a2332,stroke:#8b949e,color:#e6edf3
  class it zonaIT
  class internet zonaInternet
  class ADO,RAW,CAT,USE z
```

> Flowchart zonas = diagrama do README. HTML Archify (Live/Still) e PNG: [docs/02-arquitetura.md](docs/02-arquitetura.md).

## Documentação

| Documento | Conteúdo |
|-----------|----------|
| [docs/README.md](docs/README.md) | Índice |
| [docs/00-enquadramento.md](docs/00-enquadramento.md) | Lite/full |
| [docs/02-arquitetura.md](docs/02-arquitetura.md) | Archify + zonas |
| [docs/14-dor-dod.md](docs/14-dor-dod.md) | DoR/DoD |
| [docs/15-git-pr.md](docs/15-git-pr.md) | Git/PR |

## Azure DevOps

https://dev.azure.com/vale-devops/torre-mobilidade/_git/imagens_vale

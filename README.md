# TP01 — Integração de Sistemas de Informação (ETL)

Trabalho Prático para a UC Integração de Sistemas de Informação com o objetivo de criar um processo ETL.

Link repositório: https://github.com/mtcigor/tp01-27977

## Autor
- Igor Costa — 27977

## Pré‑requisitos
- KNIME Analytics Platform instalado
  - Download: https://www.knime.com/knime-analytics-platform

## Como executar a solução (KNIME)
1. Instale o KNIME Analytics Platform.
2. Obtenha o projeto:
   - Clonar: `git clone https://github.com/mtcigor/tp01-27977.git`
   - ou descarregar como ZIP e extrair.
3. Abra o KNIME.
4. Importe o workflow:
   - Browse
   - Selecione e aponte para a pasta do workflow deste repositório **(selecione a pasta dataint)**.
5.  Ajuste caminhos do excel
     - Atualize o nó de leitura do “Excel Reader” para apontar para a localização dos dados no seu ambiente.
6. Execute o workflow:
   - Clique direito no nó raiz do workflow e selecione “Execute” ou “Execute all”.

## Conteúdo
```
.
├── data/
│   └── input/        # Ficheiro excel com as freguesias de Portugal
├── dataint/          #Pasta que contêm o KNIME Workflow 
│    └──Rede_Eletrica_TP/ 
│       
└── doc/            # Relatório do Trabalho Prático
└── README.md/      # Ficheiro com informações sobre o repositório
```


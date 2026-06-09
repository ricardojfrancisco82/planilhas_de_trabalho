![Python3](https://img.shields.io/static/v1?label=Python3&labelColor=navy&message=ok!%E2%9C%94&style=plastic&color=lightblue&logo=python&logoColor=lightblue)
![LibreOffice](https://img.shields.io/static/v1?label=LibreOffice&labelColor=0362A1&message=ok!%E2%9C%94&style=plastic&color=BDD7EE&logo=libreoffice&logoColor=white)

# Modelos de planilhas administrativo/financeiro


### ℹ️ Informações sobre conteúdo

Modelos de planilhas de controle de trabalho administrativo/financeiro que utilizo em meu trabalho.

1. *Administrativo*
* _Controle_Contratos_v_0_2_0.ods_ planilha para controle de contratos de prestação de serviços. Permite registrar termos aditivos e ajuste de valores. Tem automações para resgate de valores, sendo necessário apenas a inserção de dados mestres do contrato, os registro de cada lançamento e dos termos aditivos/apostilamentos. Permite a emissão de uma planilha de extrato mensal, além de um ateste com opções para analise de tributação e campos para observações. AS células não editáveis estão protegidas, porém, sem senhas, para caso de algum tipo de ajuste que seja necessário realizar. Integralmente baseada em formulas do Calc em português brasileiro, sem o uso de extensões do LibreOffice, scripts python ou macros. Contém guia de uso para auxilio de preenchimento.
* _Controle_veículos_v_0_2_0_ planilha para controle de veículos em serviço, sde maneira anual, incluendio também controle de abastecimento e ocorrências de veícuilos. De maneira análoga a anterior, as celulas estão bloqueadas sem senhas para manutenção, e o arquivos mantem-se sem o uso de extensões do LibreOffice, scripts python ou macros. Contém modelo da ficha para impressão e uso (Controle_utilização_veiculos.pdf). Contém instruções d epreenchimento, além de criação de memorando e dashboard a partior dos dados inseridos.
* _Controle_Material_Expediente_v_0_1_0_ ⚙️Em andamento⚙️

📂 **Estrutura do Repositório**
```
│
|── README.md                # Explicação geral do repositório e como usar
|── .gitignore               # Essencial para não subir arquivos temporários ou dados sensíveis
|── requirements.txt         # Bibliotecas Python necessárias (pandas, openpyxl, etc.)
|
|── templates/               # Modelos de planilhas vazias e seus documentos auxiliares, quando houver (apenas a estrutura)
|   ├── administrativo/
|   |   ├── ....ods
|   │   └── ....ods
|   └── financeiro/
|       └── ....xlsx
|
|── src/                     # Código-fonte dos scripts Python
|   ├── administrativo/
|   │   ├── ....py
|   │   └── ....py
|   ├── financeiro/
|   │   ├── ...py
|   │   └── ....py
|   └── core/                # Funções compartilhadas
|       └── helpers.py
|
└── config/                  # Arquivos de configuração
    └── settings.json
```

### 📝Extensões do LibreOffice e Dependências do Python

* [VersionMgr](https://extensions.libreoffice.org/en/extensions/show/5744) - Extensão do libreoffice, prática para lidar conm versionamento e nome de arquivos.

### 📝Próximos passos
* Implementar script em pythomn que recupere a NF-e/Danfe, à partir de seu código, bem como a adição das extensões necessárias para gerencia tudo. ⚙️Em andamento⚙️



**Autor:** Ricardo Jeferson da Silva Francisco

_Junior Data Analyst | Mestre em História Social_

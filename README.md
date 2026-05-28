![Python3](https://img.shields.io/static/v1?label=Python3&labelColor=navy&message=ok!%E2%9C%94&style=plastic&color=lightblue&logo=python&logoColor=lightblue)
![LibreOffice](https://img.shields.io/static/v1?label=LibreOffice&labelColor=0362A1&message=ok!%E2%9C%94&style=plastic&color=BDD7EE&logo=libreoffice&logoColor=white)

# Modelos de planilhas administrativo/financeiro


### ℹ️ Informações sobre conteúdo

Modelos de planilhas de controle de trabalho administrativo/financeiro que utilizo em meu trabalho.

1. *Administrativo*
* _Controle_Contratos.ods_ planilha para controle de contratos de prestação de serviços. Permite registrar termos aditivos e ajuste de valores. Tem automações para resgate de valores, sendo necessário apenas a inserção de dados mestres do contrato, os registro de cada lançamento e dos termos aditivos/apostilamentos. Permite a emissão de uma planilha de extrato mensal, além de um ateste com opções para analise de tributação e campos para observações. AS células não editáveis estão protegidas, porém, sem senhas, para caso de algum tipo de ajuste que seja necessário realizar. Integralmente baseada em formulas do Calc em português brasileiro, sem o uso de extensões do LibreOffice, scripts python ou macros. Contém guia de uso para auxilio de preenchimento.
* _Controle_veiculos.ods_ planilha para controle de veículos em serviço, sendo cada planilha o controle de um mês. Integralmente baseada em formulas do Calc em português brasileiro, sem o uso de extensões do LibreOffice, scripts python ou macros. Contém modelo da ficha para impressão e uso (Controle de utilização de veiculo.pdf). No momento ainda não avaliei exatamente o que poderia melhorar para automatizar esse fluxo, ou se implemento algo a mais nessa planilha, já que ela é mais simples.

📂 **Estrutura do Repositório**
```
│
|── README.md                # Explicação geral do repositório e como usar
|── .gitignore               # Essencial para não subir arquivos temporários ou dados sensíveis
|── requirements.txt         # Bibliotecas Python necessárias (pandas, openpyxl, etc.)
|
|── templates/               # Modelos de planilhas vazias e seus documentos auxiliares, quando houver (apenas a estrutura)
|   ├── administrativo/
|   |   ├── Controle_veiculos.ods
|   │   └── Controle_Contratos.ods
|   └── financeiro/
|       └── modelo_fluxo_caixa.xlsx
|
|── src/                     # Código-fonte dos scripts Python
|   ├── administrativo/
|   │   ├── automacao_prazos.py
|   │   └── utils_admin.py
|   ├── financeiro/
|   │   ├── consolidar_orcamento.py
|   │   └── utils_fin.py
|   └── core/                # Funções compartilhadas
|       └── helpers.py
|
└── config/                  # Arquivos de configuração
    └── settings.json
```

### 📝Extensões do LibreOffice e Dependências do Python

* 

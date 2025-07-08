# Princípios Físicos da Resposta Espectral / **Physical Principles of Spectral Response**

> **PT‑BR:** Repositório do grupo da disciplina **PGSER – Princípios Físicos** (INPE) que concentra **códigos, dados, relatórios e figuras** usados na análise da **resposta espectral de diferentes alvos** (folhas, solo, etc.).
> **EN:** Repository for the **PGSER – Physical Principles** course (INPE) containing **code, data, reports and figures** used to analyse the **spectral response of various targets** (leaves, soil, etc.).

---

## 📚 Visão Geral / Overview

| PT‑BR                                                                                                                                                                                                                                      | EN                                                                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| • Explorar conceitos de interação da radiação eletromagnética com a matéria. <br>• Gerar e visualizar curvas espectrais a partir de medições de campo e catálogos. <br>• Demonstrar fluxos de processamento no Google Earth Engine e Py6S. | • Explore the interaction between electromagnetic radiation and matter. <br>• Generate and visualise spectral curves from field measurements and catalogues. <br>• Showcase processing workflows using Google Earth Engine and Py6S. |

## 🗂️ Estrutura / Repository Layout

```
Physical_principles_EM/
├── data/                # Dados brutos (CSV, ZIP de espectros handheld)
├── notebooks/           # Jupyter notebooks com análises passo‑a‑passo
├── scripts/             # Funções utilitárias em Python (pré‑processamento, plotagem)
├── reports/             # Relatórios PDF e slides
├── images/              # Figuras geradas
└── README.md            # Este arquivo / This file
```

## 🔧 Dependências / Requirements (Python ≥ 3.8)

```bash
pip install pandas matplotlib earthengine-api geemap rasterio py6s GDAL
```

| Biblioteca                   | Uso principal                       |
| ---------------------------- | ----------------------------------- |
| **pandas**                   | manipulação de CSVs de reflectância |
| **matplotlib**               | plot de curvas espectrais           |
| **earthengine-api / geemap** | acesso e visualização no GEE        |
| **rasterio & GDAL**          | leitura de GeoTIFFs                 |
| **Py6S**                     | simulação atmosférica               |

> **Nota:** notebooks assumem credenciais configuradas do **Google Earth Engine**.

## 📦 Como usar / Quick start

```bash
# clone
git clone https://github.com/Liaons/-Physical_principles_EM.git
cd Physical_principles_EM
# instale as libs principais
pip install -r requirements.txt   # (ou use o comando acima)
# abra os notebooks
jupyter lab notebooks/
```

## 👥 Autores / Authors

| Nome                               | ORCID               | E‑mail                                                                                                  |
| ---------------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------- |
| **Henrique Leão**                  | 0000-0002-6595-9576 | [paulo.leao@inpe.br](mailto:paulo.leao@inpe.br) / [Henri.leaos@gmail.com](mailto:Henri.leaos@gmail.com) |
| Manoel de Jesus de Souza Miranda   | –                   | –                                                                                                       |
| Marcus Vinicius Gonçalves da Silva | 0009-0001-9904-9001 | [marcus.silva@inpe.br](mailto:marcus.silva@inpe.br)                                                     |
| Savanah Franco de Freitas          | –                   | –                                                                                                       |

## 📄 Licença / License

Este material é disponibilizado sob a **Creative Commons Attribution‑NonCommercial 4.0 International (CC BY‑NC 4.0)**.
This work is licensed under a **Creative Commons Attribution‑NonCommercial 4.0 International (CC BY‑NC 4.0)** licence.

## ✏️ Citação / How to cite

Se usar este repositório, cite conforme abaixo:
If you use this repository, please cite it as follows:

```bibtex
@misc{leao2025_principios_fisicos_em,
  author       = {Henrique Leão and Manoel de Jesus de Souza Miranda and Marcus Vinicius Gonçalves da Silva and Savanah Franco de Freitas},
  title        = {Princípios Físicos da Resposta Espectral – PGSER/INPE},
  howpublished = {GitHub - https://github.com/Liaons/-Physical_principles_EM},
  year         = {2025},
  url          = {https://doi.org/10.5281/zenodo.15832260},
  note         = {Version 1.0. Licensed under CC BY-NC 4.0}
}
```

## 🤝 Contribuindo / Contributing

Contribuições são bem‑vindas! Abra uma *Issue* ou *Pull Request* com sugestões de melhoria.

---

> *Última atualização / Last update: 07 Jul 2025*

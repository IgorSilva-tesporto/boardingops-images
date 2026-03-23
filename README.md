# 📊 Power BI Image Repository

Repositório destinado ao armazenamento de imagens utilizadas no dashboard **Operação Embarque.**

## 📌 Objetivo
Centralizar e disponibilizar imagens de forma pública e estável, permitindo sua integração direta com o Power BI por meio de URLs no formato RAW.

## 🧩 Estrutura
Todas as imagens estão armazenadas na pasta:
```
/imagens
```

## 🔗 Utilização no Power BI
As imagens devem ser acessadas utilizando o formato de URL RAW do GitHub:

```
https://raw.githubusercontent.com/{usuario}/{repositorio}/main/imagens/{nome_arquivo}
```

Esses links devem ser utilizados como **Image URL** no **:contentReference[oaicite:1]{index=1}**.

## ⚙️ Padrão de Nomenclatura
Para garantir consistência:

- Utilizar apenas letras minúsculas  
- Não utilizar espaços (usar `-`  como espaço)
- Evitar acentos e caracteres especiais (usar `_`  como parentese)
- Manter nomes descritivos, únicos e manter o padrão  

### ✔️ Exemplo:
```
mvymcompass_porao_01.png
mvymcompass_laudo_01.png
mvymcompass_opo_des_01.png
```

## ⚠️ Boas Práticas
- Preferir imagens com tamanho inferior a 2MB  
- Manter padronização do repositório  
- Evitar estruturas complexas de pastas  

## 🚀 Observação
Este repositório é utilizado exclusivamente como suporte ao dashboard e não possui finalidade de versionamento de código.

# 📊 Power BI Image Repository

Repositório destinado ao armazenamento de imagens utilizadas no dashboard **Operação Embarque.**

## 📌 Objective
Centralizar e disponibilizar imagens de forma pública e estável, permitindo sua integração direta com o Power BI por meio de URLs no formato RAW.

## 🧩 Structure
Todas as imagens estão armazenadas na pasta:
```
/imagens
```

## 🔗 Usage in Power BI
As imagens devem ser acessadas utilizando o formato de URL RAW do GitHub:

```
https://raw.githubusercontent.com/{usuario}/{repositorio}/main/imagens/{nome_arquivo}
```

Esses links devem ser utilizados como **Image URL** no **:contentReference[oaicite:1]{index=1}**.

## ⚙️ Naming Convention
Para garantir consistência:

- Utilizar apenas letras minúsculas  
- Não utilizar espaços (usar `-`  como espaço)
- Evitar acentos e caracteres especiais (usar `_`  como parentese)
- Manter nomes descritivos, únicos e manter o padrão  

### ✔️ Example:
```
1-mvymcompass_porao_01.png
1-mvymcompass_laudo_01.png
1-mvymcompass_opo_des_01.png
2-mvhonordiva_porao_01.png
2-mvhonordiva_laudo_01.png
2-mvhonordiva_opo_des_01.png
```

## ⚠️ Best Practices
- Preferir imagens com tamanho inferior a 2MB  
- Manter padronização do repositório  
- Evitar estruturas complexas de pastas  

## 🚀 Note
Este repositório é utilizado exclusivamente como suporte ao dashboard e não possui finalidade de versionamento de código.

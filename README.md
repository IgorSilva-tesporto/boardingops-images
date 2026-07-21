
<h1 align="center">BI - Repositório de Imagens</h1>

---

Repositório destinado ao armazenamento de imagens utilizadas no dashboard **Operação Embarque.**

## Objetivo
Disponibilizar imagens de forma pública e estável, permitindo sua integração direta com o Power BI por meio de URLs no formato RAW.

## Estrutura
Todas as imagens estão armazenadas na pasta:
```
/imagens
```

## Uso no Power BI
As imagens devem ser visualizadas utilizando o formato de URL RAW do GitHub:

```
https://raw.githubusercontent.com/{usuario}/{repositorio}/main/imagens/{nome_arquivo}
```

Isso permite o link dar imagem no BI.

## Padronização dos Arquivos
Para garantir consistência:

- Não utilizar espaços, caracteres sempre juntos
- Adicionar arquivos no formato PNG (tirar print ou usar o site `I Love IMG`)
- Não incluir `MV` no nome do arquivo, independente do nome do navio
- Utilizar `_` para separar a descrição do arquivo
- Utilizar apenas letras minúsculas
- Evitar acentos e caracteres especiais 
- Manter nomes os padronizados

### Exemplo:
```
NAVIO: MV YM COMPASS
1-ymcompass_porao_01.png
1-ymcompass_opo_des_01.png
1-ymcompass_armazenado.png
1-ymcompass_exportado.png

NAVIO: HONOR DIVA
2-honordiva_porao_01.png
2-honordiva_opo_des_01.png
2-honordiva_armazenado.png
2-honordiva_exportado.png
```
Se o mesmo navio atracar denovo no terminal, adicionar "(x)" onde "x" é quantidade de vezes em que ele atracou.
```
02/01/2026: YM COMPASS
07/05/2026: YM COMPASS (2)

O ID não pode ser o mesmo de antes.
```
Se ele desatracar e atracar de novo em um período curto de tempo (você será notificado quando isso ocorrer), adicionar, nos arquivos (porão, oportunidades e desvio, exportado e armazenado) "-2a" ao final do nome.
```
05/02/2026: 10-rotterdam
06/02/2026: 11-honor diva
08/02/2026: 12-rotterdam-2a

O ID não pode ser o mesmo de antes.
```

## Boas Práticas
- Preferir imagens com tamanho inferior a 2MB  
- Manter padronização do repositório  
- Evitar estruturas complexas de pastas

---
## Observação
Este repositório é utilizado exclusivamente como suporte ao dashboard e não possui finalidade de versionamento de código.

---
website: "Sítio Autárquico - Câmara Municipal de Alcobaça"          # Entre as aspas escreve o nome do website
date: "24/02/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://www.cm-alcobaca.pt/"   # Entre as aspas escreve o domínio do website
owner: "CM Alcobaça"         # Entre as aspas escrever o nome do owner do website
a11y_statement: "https://www.cm-alcobaca.pt/acessibilidade"
seal: "Prata"                          # Entre as aspas escreve Bronze, Prata ou Ouro
validity: "27-03-2026 a 27-03-2027"    # Entre as aspas escreve o período de 1 ano de validade do Selo
status: "Concluído - Selo atribuído"      # Entre as aspas escreve o status do relatório
---

# Relatório de auditoria

Sítio Web: {{ page.website }} 

- Data de criação: {{ page.date }}
- URL: {{ page.uri }} 
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
- Validade do Selo: {{ page.validity }}
- Estado: {{ page.status }}

## Relatório {{ page.website }}

O presente relatório resultou da auditoria da informação publicada na [{{ page.a11y_statement }}](Declaração de Acessibilidade e Usabilidade).

Consulte aqui a última atualização: [Relatório {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="23032026_report.html">(23/03/2026). Relatório {{ page.website }}</a></li>
    <li><a href="17032026_report.html">(17/03/2026). Relatório {{ page.website }}</a></li>
    <li><a href="09032026_report.html">(09/03/2026). Relatório {{ page.website }}</a></li>
    <li><a href="24022026_report.html">(24/02/2026). Relatório {{ page.website }}</a></li>
  </ul>
</details>

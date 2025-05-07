# Case técnico iFood: Análise Descritiva Exploratória dos dados
## Descrição do Projeto
<p>Este Projeto é exercicío técnico proposto pelo iFood, com o objetivo de demonstrar habilidades em <b>análise descritiva</b> e <b>exploratória de dados.</b> Neste projeto tive o objetivo de dar foco na capacidade retornar Insights para a área de Marketing.</p>
<p>Embora o desafio recomende o uso apenas de Excel e/ou Google Sheets, optei por também usar Power BI para enriquecer as visualizações e facilitar a interpretação dos dados por meio de dashboards.</p>
<a href="https://docs.google.com/spreadsheets/d/1hMt7OEHsqoRIr7yyDn-v726opryyWNZkW_Cc5fWM6Ss/edit?usp=sharing">Acessem a Planilha</a>

## Tecnologias utilizadas
* <b>Excel/Google Sheets:</b> Para análise, manioulação e criação de visualizações básicas dos dados.
* <b>Power BI:</b> Para a construção de dashboards interativos e dinâmicos, facilitando a visualização dos insights.
* <b>ChatGPT:</b> Utilizando como apoio na formulação de perguntas orientadas à tomada de decisão.

## Etapas de Desenvolvimento
* <b>Definição do Objetivo:</b> O objetivo principal da análise foi identificar os clientes mais lucrativos para a empresa com o intuito de orientar a equipe de Marketing nas prócimas campanhas promocionais.

* <b>Escolha de estratégia:</b> Para está análise adotei a estratégia de <b>Pareto (regra 80/20)</b>, que parte do pressuposto de que 80% dos resultados são gerados por 20% das causas. Essa técnica foi aplicada para identificar os 20% dos clientes que geram a maior parte da receita.

* <b>Fomulação das Perguntas-Chaves:</b> Com o auxílio do ChatGPT, formulei perguntas orientadas à extração de insights que poderiam <b>ajudar a equipe de Marketing</b> a entender melhor o perfil dos principais clientes:.
 * Qual a distribuição dos 20% de clientes com maior gasto por faixa etária?
 * Qual a distribuição dos mesmos por estado civil?
 * Como se distribuem por tempo de casa (fidelidade)?
 * Qual a média de visitas mensais ao site desse grupo?
 * Quanto esses clientes gastam com vinhos (produto mais vendido)?
 * Quanto gastam com frutas (produto menos vendido)?

* <b>Identificação e Classificação dos Dados:</b> Os dados foram classificados em categorias como: Informações dos clientes, dados de compras e categoria de produto.

* <b>Análise e Agrupamento de Dados:</b> 
    * Ordenei os clientes com base no total gasto e selecionei <b>20% com maior valor de compras</b>.
    * Agrupei os dados por <b>intervalos de idade, tempo de casa, gasto com vinhos e frutas</b>(Conjunto de itens mais caros e mais baratos respectivamente), além de outras variaveis relevantes.
      <img src="https://github.com/FelipeRodrii/Case-Tecnico-iFood/blob/main/imgs/IntervalosCriados.png" width = "600px" />
    * Usei <b>tabelas dinâmicas</b> para facilitar a nálise e a criação de gráficos que evidenciam os padrões de comportamento dos clientes mais lucrativos.

    ## Visualizações e Dashboard
    * As visualizações foram inicialmente feitas em Excel/Sheets e posteriormente recriadas no power BI, visando maior interatividade.

    <table>
    <tr>
        <td><img src="https://github.com/FelipeRodrii/Case-Tecnico-iFood/blob/main/imgs/maiorGastoPorIdade.png" width="300"/></td>
            <td><img src="https://github.com/FelipeRodrii/Case-Tecnico-iFood/blob/main/imgs/maiorGastoPorEstadoCivil.png" width="300"/></td>
        <td><img src="https://github.com/FelipeRodrii/Case-Tecnico-iFood/blob/main/imgs/maiorGastoPorEstadoCivilPizza.png" width="300"/></td>
    </tr>
    <tr>
        <td><img src="https://github.com/FelipeRodrii/Case-Tecnico-iFood/blob/main/imgs/VisitasMensais.png" width="300"/></td>
        <td><img src="https://github.com/FelipeRodrii/Case-Tecnico-iFood/blob/main/imgs/maiorGastoPorVinho.png" width="300"/></td>
        <td><img src="https://github.com/FelipeRodrii/Case-Tecnico-iFood/blob/main/imgs/maiorGastoporFrutas.png" width="300"/></td>
    </tr>
    </table>

    * O dashboard final facilita a <b>compreensão visual dos insights</b> obtidos, com foco na <b>tomada de decisão estratégica</b> pela equipe de Marketing. 

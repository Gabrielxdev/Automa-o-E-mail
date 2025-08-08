#  Automação de Indicadores - OnePage de Lojas

Este projeto tem como objetivo automatizar completamente o processo de geração e envio de **OnePages** diários para uma rede de 25 lojas de roupas.

##  Sobre o Projeto

Todos os dias, os gerentes das lojas recebem um e-mail com:

* Um **relatório OnePage** (em HTML no corpo do e-mail) com os indicadores da sua loja;
* Um **arquivo Excel** em anexo com os dados completos de vendas da loja;
* Os dados de **outras lojas são protegidos**, cada gerente recebe apenas os dados da sua unidade.

A diretoria recebe um e-mail adicional com:

* Ranking **anual** e **diário** de faturamento das lojas;
* Destaques da **melhor e pior loja do dia** e do **ano**.

##  Indicadores monitorados

* **Faturamento** (meta: R\$ 1.650.000 anual / R\$ 1.000 diário)
* **Diversidade de produtos vendidos** (meta: 120 anual / 4 diário)
* **Ticket médio por venda** (meta: R\$ 500 anual e diário)

##  Tecnologias utilizadas

* Python
* Pandas
* SMTP (envio de e-mails)
* dotenv (.env para segurança de credenciais)
* EmailMessage (HTML e anexos)
* Excel e CSV

##  Organização dos arquivos

* Os arquivos de cada loja são salvos automaticamente em uma pasta com o nome da loja e a data, criando um **backup histórico**.
* Os arquivos de ranking são salvos e anexados automaticamente para a diretoria.

##  Automatização do processo

* 100% automatizado: da leitura dos dados até o envio dos e-mails.
* Segurança com variáveis de ambiente (.env).
* Relatórios visuais e objetivos com indicadores sinalizados por cores (🟢 / 🔴).

##  Exemplo de envio

Cada gerente recebe um e-mail personalizado com os resultados do dia, metas atingidas e uma planilha anexa com os dados de sua loja.

---

Este projeto simula um processo real de automação corporativa com foco em eficiência, segurança de dados e comunicação clara entre áreas.

e-Social Schema
===============

XML Schemas do e-Social desenvolvidos pelo [Instituto Stela®](http://stela.org.br/portal/).

Haja visto que estes arquivos não são "oficiais" e foram transcritos do
[manual do e-Social](http://www.esocial.gov.br/doc/MOS_V_1_1_Publicacao.pdf)
divulgado pelo Governo, eles podem conter alguns erros e/ou mesmo diferentes formas de
modelagem em relação aos arquivos oficialmente utilizados pela Previdência Social.
Portanto, **utilize-os com critério.**

**VERSÃO UTILIZADA: 1.1 de 06 de Janeiro de 2014.**

Bug reports e sugestões:
------------------------
Como a ajuda da comunidade é sempre bem-vinda, por favor reportem qualquer bug encontrado na página 
[issues](https://github.com/instituto-stela/esocial-schema/issues) no GitHub. Contudo, evitem a
duplicidade de informação verificando se o problema já não foi reportado.

Além disso, toda sugestão e/ou contribuição através de Pull Requests será analisada e,
se possível, incorporada ao XML Schema do e-Social.

Listagem de Schemas:
--------------------
* **Esocial:** Arquivo raiz do XML Schema do e-Social
* **S_1000:** Informações do Empregador/Contribuinte
* **S_1010:** Tabela de Rubricas
* **S_1020:** Tabela de Lotações
* **S_1030:** Tabela de Cargos
* **S_1040:** Tabela de Funções
* **S_1050:** Tabela de Horários/Turnos de Trabalho
* **S_1060:** Tabela de Estabelecimentos e Obras de Construção Civil
* **S_1070:** Tabela de Processos Administrativos/Judiciais
* **S_1080:** Tabela de Operadores Portuários
* **S_1100:** Eventos Periódicos - Abertura
* **S_1200:** Eventos Periódicos - Remuneração do Trabalhador
* **S_1300:** Eventos Periódicos - Pagamentos Diversos
* **S_1310:** Eventos Periódicos - Serviços Tomados mediante Cessão de Mão de Obra
* **S_1320:** Eventos Periódicos - Serviços Prestados mediante Cessão de Mão de Obra
* **S_1330:** Eventos Periódicos - Serviços Tomados de Cooperativa de Trabalho
* **S_1340:** Eventos Periódicos - Serviços Prestados pela Cooperativa de Trabalho
* **S_1350:** Eventos Periódicos - Aquisição de Produção
* **S_1360:** Eventos Periódicos - Comercialização da Produção
* **S_1370:** Eventos Periódicos - Recursos Recebidos ou Repassados para Associação Desportiva que mantenha equipe de Futebol Profissional
* **S_1380:** Eventos Periódicos - Informações complementares - Desoneração
* **S_1390:** Eventos Periódicos - Receita de Atividades Concomitantes
* **S_1399:** Eventos Periódicos - Fechamento
* **S_1800:** Eventos Periódicos - Espetáculo Desportivo
* **S_2100:** Cadastramento Inicial do Vínculo
* **S_2200:** Admissão de Trabalhador
* **S_2220:** Alteração de Dados Cadastrais do Trabalhador
* **S_2240:** Alteração de Contrato de Trabalho
* **S_2260:** Comunicação de Acidente de Trabalho
* **S_2280:** Atestado de Saúde Ocupacional
* **S_2320:** Afastamento Temporário
* **S_2325:** Alteração de Motivo de Afastamento
* **S_2330:** Retorno de Afastamento Temporário
* **S_2340:** Estabilidade - Início
* **S_2345:** Estabilidade - Término
* **S_2360:** Condição Diferenciada de Trabalho - Início
* **S_2365:** Condição Diferenciada de Trabalho - Término
* **S_2400:** Aviso Prévio
* **S_2405:** Cancelamento de Aviso Prévio
* **S_2600:** Trabalhador Sem Vínculo de Emprego - Início
* **S_2620:** Trabalhador Sem Vínculo de Emprego - Alteração Contratual
* **S_2680:** Trabalhador Sem Vínculo de Emprego - Término
* **S_2800:** Desligamento
* **S_2820:** Reintegração
* **S_2900:** Exclusão de Eventos
* **Shared_Complex_Types:** ComplexTypes compartilhados pelos layouts do eSocial
* **Shared_Simple_Types:** SimpleTypes compartilhados pelos layouts do eSocial

Observações
-----------
Embora os XML Schemas do e-Social desenvolvidos pelo [Instituto Stela®](http://stela.org.br/portal/)
possam ser utilizados para a validação dos arquivos antes de sua transmissão para a previdência
social, é importante ressaltar que este não é o objetivo principal do desenvolvimento deste modelo.

Grande parte das validações descritas no [manual do e-Social](http://www.esocial.gov.br/doc/MOS_V_1_1_Publicacao.pdf)
não podem ser implementadas em nível de XSD, portanto, é de extrema importância a leitura e o entendimento
deste manual no momento da homologação das transmissões.

Por fim, este modelo foi desenvolvido principalmente para a geração automática de código de sistemas
extratores de informação de arquivos já transmitidos e validados do e-social. Assim, alguns modelos 
adotados, embora não sejam os mais eficiêntes na utilização usual de um arquivo XSD, atendem às necessidades
de implementação e de documentação deste código automaticamente gerado.
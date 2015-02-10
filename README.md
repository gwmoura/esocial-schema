e-Social Schema
===============

XML Schemas do e-Social desenvolvidos pelo [Instituto Stela®](http://stela.org.br/portal/).

Haja visto que estes arquivos não são "oficiais" e foram transcritos do
manual do eSocial, eles podem conter alguns erros e/ou mesmo diferentes formas de
modelagem em relação aos arquivos oficialmente utilizados pela Previdência Social.
Portanto, **utilize-os com critério.**

**VERSÃO UTILIZADA: 2.0 de Dezembro de 2014.**

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
* **Shared_Complex_Types:** ComplexTypes compartilhados pelos layouts do eSocial
* **Shared_Simple_Types:** SimpleTypes compartilhados pelos layouts do eSocial

Observações
-----------
Embora os XML Schemas do e-Social desenvolvidos pelo [Instituto Stela®](http://stela.org.br/portal/)
possam ser utilizados para a validação dos arquivos antes de sua transmissão para a previdência
social, é importante ressaltar que este não é o objetivo principal do desenvolvimento deste modelo.

Grande parte das validações descritas no manual do eSocial não podem ser implementadas em nível de XSD, portanto, é de extrema importância a leitura e o entendimento
deste manual no momento da homologação das transmissões.

Por fim, este modelo foi desenvolvido principalmente para a geração automática de código de sistemas
extratores de informação de arquivos já transmitidos e validados do e-social. Assim, alguns modelos 
adotados, embora não sejam os mais eficiêntes na utilização usual de um arquivo XSD, atendem às necessidades
de implementação e de documentação deste código automaticamente gerado.

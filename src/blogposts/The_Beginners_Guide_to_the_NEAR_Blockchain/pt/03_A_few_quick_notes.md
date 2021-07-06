## Algumas observações rápidas…

Existem alguns tipos de projetos que até se encaixam no escopo, mas que não serão aprofundados aqui:

1. **Moedas:** Fundamentalmente, qualquer token pode operar como uma moeda porque você pode usá-lo como uma unidade contábil, um meio de troca e/ou uma reserva de valor. Mas algumas blockchains vem sendo criadas especificamente para atuar tanto como moedas (Bitcoin, Zcash, Monero...), ou para operar diretamente no mundo das moedas (Ripple, Stellar, Libra). Estas não são plataformas de computação genéricas, as quais nós estamos focando aqui, então eu vou deixar isso de lado.

2. **Blockchains privadas:** Algumas blockchains, como o projeto Hyperledger da Linux Foundation's ou R3 Corda, se apresentam para grandes empresas como um tipo de blockchain mais segura, pois elas permitem que essas companhias controlem todos os nós na rede. Já que NEAR também tem a capacidade de prover privacidade nesses fragmentos da rede, ignorarei essa categoria de chains também, pois a grande vantagem na segurança advêm da ampla descentralização pública, e não de construir um oligopólio com poucas grandes empresas controlando a rede.

3. **GDAs (DAGs): ** Esse é a mais complicado, pois essas chains jogam num mundo de blockchains e estão, essencialmente, fazendo o mesmo tipo de coisa - criando livros razão imutáveis (que apenas anexam). O termo "GDAs" vêm da ciência da computação e significa "Grafo Direcionado Acíclico" (em inglês DAG, "Directed Acyclic Graph"), que é a real estrutura de dados que os compõe. Falando genericamente, esses projetos, como IOTA, tendem a construir uma bagunça complicada de transações entre muitos pequenos dispositivos, e que funciona muito similarmente a uma blockchain. Isso é escalável, mas tem vários desafios quanto à segurança e implementação. Não me aprofundarei nisso, mas não se esqueça sobre os GDAs, pois várias chains, incluindo a NEAR, usam um tipo de GDA menor em algum lugar no processo de construção dos blocos.
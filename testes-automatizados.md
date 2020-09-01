# Teste Automatizados

Servem para que nossa aplicação continue funcionando independente do número de novas funcionalidades e do número de devs no time.


1. Testes unitários  (um arquivo de forma isolada)
- Testam funcionalidades específicas da nossa aplicação (precisam ser funções puras,  não dependem de outra parte da aplicação, (Jamais: chamadas a API, efeito colateral, serviços externos)

2. Teste de Integração ( testa todo o fluxo de uma funcionalidade)
Testam uma funcionalidade completa, passando por várias camadas da aplicação. Ex:Route -> Controller-> Serviço -> Repositório ... ( Todas as camadas )

3. Teste E2E (Interface)
- Teste que simulam a ação do usuário dentro da nossa aplicação
- Simular o usuário utilizando
Ex: Clique no input de usuário -> Digite Email -> Clique no botão Submit

4. TDD (Test Driven Development) Desenvolvimento dirigido a testes
ex: Quando cadastrar na aplicação, ele deve receber um email de boas vindas


## JEST


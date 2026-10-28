\# Testes automatizados — Gabriela



\## Objetivo



Ampliar a cobertura dos testes automatizados das regras de negócio do FinTrack para a Menção 1 de Integração DevOps.



\## Arquivo principal



Os testes foram implementados em:



```text

tests/unit/business.test.ts


GET após exclusão: comprova que a tarefa excluída não aparece mais na listagem.

Erro 422: comprova o tratamento de dados de entrada inválidos.

Erro 404: comprova o tratamento de identificadores inexistentes.

GitHub Actions: comprova a execução automatizada da suíte de testes.

Docker: comprova a configuração do ambiente containerizado.





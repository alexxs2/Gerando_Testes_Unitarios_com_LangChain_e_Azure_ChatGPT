# Gerando Testes Unitários com LangChain e Azure ChatGPT

Este pequeno projeto teve como objetivo principal entender e experimentar como usar o LangChain para gerar e executar testes unitários em código Python. A ideia foi construir um fluxo simples em que um agente do LangChain, com acesso a uma REPL Python, escreve funções (ou recebe funções existentes) e executa asserts para verificar comportamento imprimindo uma mensagem de sucesso quando todos os testes passam.

No desenvolvimento foram validados elementos práticos: como configurar o ambiente (instalar langchain, langchain-openai, openai e dependências opcionais para execução local), como instanciar o PythonREPLTool e criar um agente zero-shot que recebe instruções para implementar funções e rodar testes.

O repositório contém exemplo mínimo que podem ser executados em Colab: uma célula de instalação das dependências, a configuração segura da variável de ambiente para a chave (ou uso de Azure AD) e um bloco de código que cria o agente e pede para implementar uma função de exemplo (por exemplo, is_prime) e rodar asserts correspondentes.

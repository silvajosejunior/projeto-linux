# projeto-linux

# Script de Instalação do Apache e Implantação de Site

Este é um script em Bash que automatiza o processo de atualização do sistema, instalação do servidor web Apache2 e implantação de um site a partir de um repositório no GitHub.

## Funcionalidades

- Atualiza o sistema operacional.
- Instala o servidor web Apache2.
- Baixa um repositório do GitHub.
- Implanta o site a partir do repositório no diretório `/var/www/html/`.

## Uso

1. **Execução**:
   - Certifique-se de que você tenha permissões adequadas para executar este script. Você pode usar o comando `chmod +x seu_script.sh` para conceder permissões de execução.
   - Execute o script no terminal:
     ```bash
     ./seu_script.sh
     ```

2. **Siga as instruções**:
   - O script irá atualizar o sistema, instalar o Apache2 e baixar um repositório do GitHub.
   - O site será implantado no diretório `/var/www/html/`.

## Notas

- Este script assume que você está executando-o em um sistema baseado no Debian (como o Ubuntu).
- Certifique-se de que o servidor Apache2 não está em conflito com outro serviço web em execução, caso contrário, ajuste a configuração de porta conforme necessário.
- Certifique-se de que o arquivo `.zip` no URL fornecido está sempre disponível e contém o conteúdo esperado.

## Licença

- Este script está licenciado sob a [MIT] - consulte o arquivo `LICENSE` para obter detalhes.

# FREE AGENTE Beta 0.2.0

**Beta público gratuito para Windows 10/11 (64 bits)**. Ferramentas MCP para listar, ler e escrever arquivos de texto apenas na pasta autorizada do próprio computador.

[Baixar FREE AGENTE Beta](https://github.com/elgato2221/free-agente-beta/releases/download/v0.2.0-beta/free-agente-0.2.0-beta-win-x64.zip) · [Site e instruções](https://elgato2221.github.io/free-agente-beta/) · [Privacidade](docs/privacidade.html) · [Suporte](https://github.com/elgato2221/free-agente-beta/issues)

## Instalação

1. Baixe o ZIP em Releases e extraia todos os arquivos em uma pasta gravável.
2. Execute INICIAR_FREE_AGENTE.cmd. O Node.js e o Cloudflared já estão inclusos.
3. Execute COPIAR_LINK.cmd para copiar o endereço MCP. Não o compartilhe.
4. No cliente ChatGPT/Claude que permita MCP personalizado, cadastre esse endereço sem autenticação adicional; os dados secretos já estão no endereço.
5. Coloque arquivos de texto na pasta Documentos/Free Agente/area-de-trabalho e autorize apenas as operações desejadas.

## Estado real do produto

- **Disponível no beta:** listar arquivos, ler arquivos de texto e gravar arquivos de texto até 1 MB por arquivo na pasta autorizada, com cota experimental local.
- **Não disponível:** shell, execução de testes, instalação de apps, memória entre chats, assinaturas Stripe, link fixo, publicação no diretório público do ChatGPT.
- O endereço do túnel gratuito Cloudflare muda a cada reinício.
- A disponibilidade de MCP personalizado depende do cliente de IA e do plano contratado.
- **Não é afiliado** à OpenAI, Anthropic nem Cloudflare.

## Segurança e privacidade

Uma instalação recém-extraída gera credencial própria. Os arquivos ficam em uma pasta local; conteúdo lido pode ser transmitido pelo túnel Cloudflare para o cliente de IA. Faça backup dos arquivos importantes. Nunca publique seu endereço MCP pessoal nem o token. Leia [Privacidade](docs/privacidade.html) e [Termos](docs/termos.html).

## Suporte

Abra [Issues](https://github.com/elgato2221/free-agente-beta/issues). Para vulnerabilidades, use [relatos privados](https://github.com/elgato2221/free-agente-beta/security/advisories/new). Não publique dados pessoais ou tokens.

## Download e verificação

O release possui free-agente-0.2.0-beta-win-x64.zip e checksum free-agente-0.2.0-beta-win-x64.zip.sha256. O pacote inclui licenças de terceiros e um arquivo LEIA_PRIMEIRO.txt.

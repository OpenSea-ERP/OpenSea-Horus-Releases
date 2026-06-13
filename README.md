# OpenSea Horus

Registro de ponto por quiosque — QR Code e reconhecimento facial, integrado ao OpenSea ERP.

## O que é

O OpenSea Horus é um aplicativo de desktop que transforma um computador com webcam em um terminal de ponto. O colaborador registra entrada e saída aproximando-se da câmera (reconhecimento facial) ou apresentando seu QR Code, sem filas e sem cartão de papel.

É um aplicativo satélite do OpenSea ERP: as marcações fluem automaticamente para o sistema central, onde ficam disponíveis para o RH e a folha de pagamento. O app se mantém atualizado sozinho, sem necessidade de reinstalação manual.

> **Versão beta (release candidate).** Esta é uma versão de pré-lançamento (`v0.1.0-rc4`), destinada a testes e validação. Pode conter instabilidades e mudanças entre versões. Não recomendada para uso em produção crítica.

## Download

Baixe a versão mais recente em **[Releases](https://github.com/OpenSea-ERP/OpenSea-Horus-Releases/releases/latest)**.

| Sistema | Arquivo | Recomendado para |
| --- | --- | --- |
| Windows (instalador) | `OpenSeaHorus-Setup-0.1.0-rc4.exe` | Instalação individual em um terminal |
| Windows (pacote MSI) | `OpenSeaHorus-Setup-0.1.0-rc4.msi` | Instalação gerenciada / implantação em rede |

Na maioria dos casos, use o instalador `.exe`. O pacote `.msi` é voltado a ambientes corporativos que distribuem software via política de grupo (GPO) ou ferramentas de gestão de máquinas.

> **Atualização automática.** Após instalado, o OpenSea Horus verifica e aplica novas versões sozinho. Não é preciso baixar e reinstalar manualmente a cada atualização.

## Requisitos

- Windows 10 ou 11 (64 bits).
- Webcam para reconhecimento facial e leitura de QR Code.
- Conexão com a internet para sincronizar as marcações com o OpenSea ERP e receber atualizações.
- Conta e ambiente OpenSea ERP configurados.

## Suporte

<!-- TODO: definir canal de suporte (e-mail, telefone ou link de documentação) -->

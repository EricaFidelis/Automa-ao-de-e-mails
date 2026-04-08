# Automa-ao-de-e-mails

🚀 Automação de E-mails com Python & Outlook
Este projeto é uma ferramenta de automação industrial/comercial desenvolvida para otimizar o disparo de e-mails personalizados. O sistema utiliza uma interface gráfica moderna e se integra diretamente ao Microsoft Outlook para garantir a entregabilidade e o registro dos envios.

✨ Características de Clean Code
Este repositório foi desenvolvido seguindo princípios de Código Limpo para garantir fácil manutenção e legibilidade:

Responsabilidade Única: Cada função executa apenas uma tarefa (envio, formatação, interface).

Constantes Globais: Configurações de cores e caminhos centralizadas para fácil alteração de identidade visual.

Segurança de Dados: O código é fornecido sem credenciais ou dados sensíveis expostos (Clean Version).

Interface Intuitiva: Uso da biblioteca CustomTkinter para uma experiência de usuário (UX) moderna em modo escuro.

🛠️ Funcionalidades
Disparo em Lote: Envio sequencial de e-mails com delay para evitar bloqueios.

Personalização Dinâmica: Substituição automática de tags como {name} no corpo do e-mail.

Botões Interativos (CTA): Inclusão de botões de resposta rápida via protocolo mailto.

Anexos Múltiplos: Interface para seleção de arquivos via gerenciador do Windows.

Persistência: Salva configurações de perfil e botões em um arquivo JSON local.

📋 Pré-requisitos
Para rodar este projeto, você precisará de:

Python 3.10 ou superior.

Microsoft Outlook instalado e configurado com uma conta ativa.

Bibliotecas listadas no comando abaixo.

🚀 Como instalar
Clone o repositório:

Bash
git clone https://github.com/seu-usuario/seu-repositorio.git
Instale as dependências:

Bash
pip install pywin32 customtkinter pillow
Execute o programa:

Bash
python disparo.py
📦 Como gerar o Executável (.exe)
Para distribuir o programa para outros usuários que não possuem Python:

Instale o PyInstaller: pip install pyinstaller

Rode o comando:

PowerShell
python -m PyInstaller --noconsole --onefile --add-data "logo.png;." --add-data "banner.jpg;." disparo.py
O arquivo final estará na pasta /dist.

📝 Notas de Uso
Certifique-se de que as imagens logo.png e banner.jpg estejam na raiz do projeto para que a assinatura seja exibida corretamente.

O formato padrão de entrada para contatos é: Nome do Cliente, email@exemplo.com (um por linha).

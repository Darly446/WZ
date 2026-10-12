# WORLD ERZES — protótipo PWA

## Abrir localmente
Abra `index.html` para uma prévia visual. Para testar instalação e service worker, sirva a pasta por HTTPS ou localhost.

## Incluído
- Tela de carregamento com as cinco imagens fornecidas, em sequência.
- Tela inicial WORLD ERZES com os botões Clã, Mercado clandestino e Loja do mago.
- Navegação do sistema de clãs.
- Primeira tela de perfil: botão muda de “Criar” para “Perfil” depois de salvar.
- Formulário de perfil com gamertag, Discord, estilo de jogo, descrição e seleção entre 10 avatares medievais (emojis provisórios).
- Edição e visualização do perfil no mesmo navegador usando armazenamento local.
- Formulário de pré-cadastro com nome obrigatório, tag curta e descrição/objetivo.
- Manifest e service worker para base PWA.
- Música medieval incluída localmente: toca a faixa completa, aguarda 2 minutos após o fim e reinicia; botão de controle na barra superior. O primeiro toque do usuário habilita o áudio em navegadores móveis.

## Limitações atuais
Este pacote é uma versão inicial funcional de interface/PWA, ainda não é o sistema online completo. O perfil é salvo apenas no armazenamento local deste navegador; os demais dados ainda não são persistidos nem sincronizados entre jogadores. O envio do formulário apenas demonstra os dados localmente; não envia pedidos ao Taurus. O login Discord ainda não está conectado. Antes de uso real, integrar banco de dados (ex.: Supabase), Discord OAuth2, regras de autorização no servidor, painel administrativo e atualizações em tempo real. Não inserir senha do Discord neste protótipo.

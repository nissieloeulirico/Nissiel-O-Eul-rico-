# Configuração pública do GitHub

A estrutura de leitura, os metadados e os arquivos de descoberta já estão no repositório. Algumas opções dependem das configurações da conta e precisam ser ativadas na interface do GitHub.

## 1. Publicar a biblioteca digital

1. Abra https://github.com/nissieloeulirico/Nissiel-O-Eul-rico-/settings/pages
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch **main**.
4. Na pasta, selecione **/docs**.
5. Clique em **Save**.
6. Aguarde a publicação e use **Visit site** para confirmar o endereço.

Endereço esperado: https://nissieloeulirico.github.io/Nissiel-O-Eul-rico-/

O repositório já contém a página inicial, sete páginas de leitura, CSS em tom de papel marfim, sitemap.xml, robots.txt e llms.txt. O GitHub Pages precisa ser ativado para servir esses arquivos publicamente.

## 2. Criar o README do perfil

O arquivo [PROFILE-README.md](PROFILE-README.md) está pronto como texto-base. Para que apareça no topo do perfil:

1. Crie um repositório público chamado exatamente **nissieloeulirico**.
2. Adicione um arquivo **README.md** na raiz.
3. Copie para ele o conteúdo de [PROFILE-README.md](PROFILE-README.md).

O GitHub só exibe esse bloco automaticamente quando o repositório público tem o mesmo nome do nome de usuário.

## 3. Adicionar tópicos ao repositório

Na página principal do repositório, use o ícone de edição da seção **About** e adicione estes tópicos:

- poesia
- literatura
- poesia-brasileira
- literatura-brasileira
- acervo-literario
- poemas
- autor-independente
- literatura-portuguesa
- creative-writing
- nissiel-o-eulirico

Os tópicos ajudam a classificar o projeto nas buscas internas do GitHub. Use apenas os que descrevem de fato o conteúdo.

## 4. Imagem de compartilhamento

Em **Settings → General → Social preview**, carregue a arte de capa escolhida para o repositório. A imagem de prévia aparece quando o endereço do repositório é compartilhado em plataformas compatíveis.

A imagem não foi alterada automaticamente nesta etapa: a configuração de Social preview exige upload pela interface do GitHub.

## 5. Conferência final

Depois de ativar o Pages:
- abra a página inicial e cada poema;
- confirme que o fundo marfim e a tipografia aparecem corretamente;
- abra `/sitemap.xml` e `/llms.txt`;
- teste os links para WordPress e para os arquivos-fonte.

Não envie o sitemap a serviços externos antes de confirmar que o site está publicado.

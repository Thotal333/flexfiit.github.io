
��#   F l e x - F i t 
PARTICIPANTES:
Danilo lima Cruz  RA:5102146
Marcelo Mousinho de Pontes Cardoso RA:5083486
Thomas Ramos de Almeida  RA:5104106
Ian de Jesus Souza  RA:5172071
Kauã Gomes nobre  RA:5206600
 


SLIDES: https://www.canva.com/design/DAGEmSkZ3dc/RtPW2VF6NJawXA7QYDzAgw/edit?utm_content=DAGEmSkZ3dc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton



DOCUMENTAÇÃO GERAL:

Documentação do Código HTML

Introdução:
Este é um documento HTML que descreve um site para uma academia chamada Flex Fit. O site contém várias seções, incluindo Início, Sobre, Nossos Serviços, Preços, Treinadores, blogs e um rodapé com links rápidos, horário de funcionamento, contatos e opção de inscrição para novidades.

Estrutura:
1. *Cabeçalho (<header>):*
    - Contém o logotipo da academia e um menu de navegação.
2. *Principal (<main>):*
    - Contém várias seções, incluindo Início, Sobre, Nossos Serviços, Preços, Treinadores, blogs e um banner promocional.
3. *Seção de Início (<section id="home">):*
    - Apresenta um slider com imagens de pessoas na academia e um botão de chamada para ação.
4. *Seção Sobre (<section id="about">):*
    - Fornece informações sobre a academia, incluindo sua missão e valores.
5. *Seção de Nossos Serviços (<section id="features">):*
    - Apresenta os serviços oferecidos pela academia, como musculação para homens e mulheres.
6. *Seção de Preços (<section id="pricing">):*
    - Lista os planos de preços oferecidos pela academia.
7. *Seção de Treinadores (<section id="trainers">):*
    - Apresenta os treinadores da academia, incluindo suas fotos e links para redes sociais.
8. *Seção de Feedback (<section class="review">):*
    - Exibe feedbacks dos clientes em um slider.
9. *Seção de Blogs (<section id="blogs">):*
    - Apresenta postagens diárias do blog da academia em um slider.
10. *Rodapé (<footer>):*
    - Contém links rápidos, horário de funcionamento, informações de contato e opção de inscrição para novidades.

Recursos Externos:
- O código faz referência a um arquivo de estilo externo (style.css).
- Ele também usa as bibliotecas externas Font Awesome e Swiper para ícones e funcionalidades de slider, respectivamente.
Scripts:
- O código faz referência a um arquivo JavaScript externo (index.js), que provavelmente contém scripts para funcionalidades interativas do site.
Esta documentação fornece uma visão geral do código HTML e de sua estrutura, ajudando na compreensão e manutenção do site.

Código HTML: https://github.com/Thotal333/flexfiit.github.io/blob/main/index.html


 
Documentação do Código CSS


Este arquivo CSS estiliza a página da FlexFit, tornando a mesma mais responsiva e estilizada. A partir disso temos as sequintes utilizações:

1. *Importação de Fonte Externa:*
   - A importação da fonte Nunito do Google Fonts para uso no documento.
2. *Reset de Estilos:*
   - Definições para elementos HTML básicos para reiniciar os estilos padrão do navegador.
   - Inclui a definição de margem, preenchimento e caixa de limite (box-sizing).
   - Remoção de decoração de texto, contornos e bordas.
   - Transformação de texto para capitalizado.
   - Transição suave para todas as propriedades.
3. *Estilos Gerais:*
   - Definição do tamanho da fonte base para 62.5% do tamanho padrão do navegador.
   - Comportamento de rolagem suave.
   - Ocultação da barra de rolagem horizontal.
   - Estilização da barra de rolagem.
4. *Estilos do Corpo (Body):*
   - Fundo preto para o corpo da página.
5. *Estilos das Seções (Section):*
   - Preenchimento para as seções da página.
6. *Estilos do Cabeçalho (Heading):*
   - Centralização do texto.
   - Adição de um sublinhado para separação visual.
   - Estilização do texto do cabeçalho e dos botões.
7. *Estilos do Menu de Navegação (Header):*
   - Estilização do menu de navegação fixo no topo da página.
   - Estilização do logotipo e dos links de navegação.
8. *Estilos da Página Inicial (Home):*
   - Estilização dos slides e conteúdo da página inicial.

9. *Estilos Sobre (About):*
   - Estilização das seções "Sobre" da página.
10. *Estilos de Recursos (Features):*
    - Estilização dos recursos da página, como boxes com imagens e texto.
11. *Estilos de Preços (Pricing):*
    - Estilização dos planos de preços e informações relacionadas.
12. *Estilos dos Instrutores (Trainers):*
    - Estilização das seções de instrutores, incluindo imagens e informações.
13. *Estilos do Banner (Banner):*
    - Estilização do banner principal da página.
14. *Estilos de Avaliações (Review):*
    - Estilização das seções de avaliações, incluindo slides e informações dos usuários.
15. *Estilos dos Blogs (Blogs):*
    - Estilização das seções de blogs, incluindo imagens e texto.
16. *Estilos do Rodapé (Footer):*
    - Estilização do rodapé da página, incluindo links e informações de contato.
17. *Media Queries (Consultas de Mídia):*
    - Definições de estilo para diferentes tamanhos de tela, tornando o site responsivo.

Código CSS: https://github.com/Thotal333/flexfiit.github.io/blob/main/style.css
 
Documentação do Código JavaScript

Introdução:
Este código JavaScript adiciona funcionalidades interativas ao site da academia Flex Fit. Ele controla a exibição do menu de navegação em dispositivos móveis e configura sliders em diferentes seções do site.

Funcionalidades:
1. *Controle do Menu:*
    - O código permite que o menu de navegação seja exibido ou oculto em dispositivos móveis quando o ícone do menu é clicado.
    - Quando o ícone do menu é clicado, ele alterna entre a classe fa-times, que exibe um ícone de fechar, e a classe padrão, que exibe um ícone de barras.
    - Além disso, a classe active é adicionada ou removida da barra de navegação para mostrar ou ocultar o menu.
    - O menu também é automaticamente oculto quando o usuário rola a página.
2. *Configuração dos Sliders:*
    - O código configura três sliders diferentes em diferentes seções do site: um na seção de Início, um para feedbacks e outro para blogs.
    - Cada slider é configurado usando a biblioteca Swiper.
    - Eles possuem várias opções, como espaço entre os slides, efeito de fade, cursor de agarrar, loop infinito, tempo de reprodução automática e slides centrados.
    - Os sliders de feedbacks e blogs também possuem breakpoints para ajustar o número de slides exibidos em diferentes tamanhos de tela.
Recursos Utilizados:
- O código utiliza a biblioteca Swiper para configurar os sliders em diferentes seções do site.
Esta documentação fornece uma visão geral das funcionalidades implementadas pelo código JavaScript, ajudando na compreensão de como ele interage com o site da academia Flex Fit.

Código JavaScripit: https://github.com/Thotal333/flexfiit.github.io/blob/main/index.js

Código completo no GitHub: https://github.com/Thotal333/flexfiit.github.io/








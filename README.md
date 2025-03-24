# Checklist-Acessibilidade


>>Elementos não textuais<<

1- Todas as imagens têm um texto alternativo (alt) 
sim(x) não()"
Meu projeto possui esses elementos pois faz sentido para meu projeto, embora a maioria das imagens do projeto serão fotos de publicações dos próprios usuários, ou seja, cada foto será diferente. Porém, o projeto será desenvolvido com react native, logo, utilizarei a propriedade "accessibilityLabel"

2- Os itens não textuais têm uma versão alternativa em texto
sim(x) não()
Meu projeto possui esse elemento. O elemento de alternativa em texto faz sentido, já que o projeto visa a acessibilidade para pessoas com deficiências visuais. O usuário, para se sentir incluído na aba comunidade, deve sempre ter ciência de uma postagem com um elemento não textual, como fotos ou gráficos.

3- Não são usadas imagens que contêm blocos de texto
sim() não(x)
Embora todos os textos serem configurados como elementos textuais, apenas a logo da tela inicial do projeto possui um texto - sendo este, o próprio nome do aplicativo. Esse elemento de acessibilidade faz sentido para o projeto, tanto pela facilidade de construção, como para deficientes visuais utilizarem o aplicativo sem maiores dificuldades.

>>Formulários<<

1- Todos os campos dos formulários têm uma <label> associada
sim(x) não()
Esse campo faz sentido para o projeto, visto que ajuda a identificação dos campos para os usuários que usam configuarções assistivas para identificar elementos textuais. Sendo assim, será implementado no projeto, utilizando propriedades como accessibilityLabel

2- São usados <fieldset> e <legend> para agrupar os vários campos nos formulários
sim() não(x)
Não estarei utilizando no  meu projeto, pois não haverão diversos formulários. Entretanto, as  funcionalidades como cadastro, login e até mesmo postagens terão tags, como a própria <label> associada para a identificação do elemento textual e da caixa de input. Não fará sentido no projeto por questões visuais e organização da tela.

3- O envio dos formulários é feito via input/button e não através de links e JavaScript
sim() não(x)
Como o react native utiliza propriedades diferentes como o Button, não terei o problema do JavaScript não acompanhar, pois as funcionalidades já são nativas do react native, logo, essa funcionalidade não faz sentido para meu projeto, mas usarei todas as propriedades necessárias para garantir que o dispositivo reconheça botões de envios de formulários/postagens

4- Os erros nos formulários são indicados em texto e junto do campo que contém o erro
sim(x) não()
Como qualquer tipo de usuário, caso faça algo errado, o usuário precisa ser notificado e orientado para utilizar a aplicação de forma correta. Pensando na experiência do usuário ao preencher um tipo de formulário, essa opção deve ser implementad, pois faz total sentido, para que o usuário não se sinta perdido caso a aplicação não aceite o que o usuário tentar passar pelo formulário.

>>Uso da cor e elementos que piscam<<

1- Não é usada apenas a cor para transmitir informação
sim(x) não()
Pensando na experiência do usuário, para que a navegação seja clara e visível, ou a identificação de alguma aba, serão implementados elementos como simbolos ou textos para orientar o usuário. 

2- Não há elementos que piscam ou mudam de cores repetidamente
sim(x) não()
No projeto, não serão implementadas mudanças de cores piscando. A estética do projeto é pensada em uma paleta de cores monocromática, mudando apenas tons da cor verde em diferentes telas, pensando em trazer a sensação de leveza, tranquilidade e clareza nas informações. Não faz sentido para o projeto, implementar funções com cores piscando para chamar a atenção, além de poder causar danos nas vistas e prejudicar pessoas com epilepsia

>>Navegação<<

1- São fornecidos atalhos para saltar links repetitivos
sim(x) não()
Os atalhos estão presentes em um offcanvas acessado pelo botão de menu no canto superior esquerdo da aplicação. Esses atalhos visam melhorar a experiência do usuário, sem ter que navegar por muitos lugares para acessar a página que ele deseja utilizar em específico, além de beneficiar e otimizar a usabilidade do aplicativo para pessoas que utilizam tecnologias assistivas para navegar.

2- O <title> das páginas é claro, direto e percetível e está intimamente relacionado com o conteúdo da mesma
sim() não(x)
Por ser uma aplicação mobile, tags ou propriedades não se aplicam no projeto, já que não terão títulos como em aplicações web. Entretanto, os títulos das páginas serão bem legíveis e intuitivos, visto que pessoas com deficiências visuais ou até mesmo com idades mais avançadas possuem mais difiiculdade de identificar a função da página.

3- O site é navegável usando apenas o teclado
sim() não(x)
Pensando na navegação totalmente manual e touch, a função de navegação com o teclado não será aplicada. O dispositivo que visa rodar o projeto é totalmente comandado por toques na tela.

>>Semântica e Legibilidade<<

1- O conteúdo está estruturado de forma semântica
sim(x) não()
Visando a legibilidade e fácil identificação das opções visíveis na tela, o conteúdo será estruturado seguindo uma hierarquia. Isso facilita a leitura do usuário e ajuda na absorção de informações.

2- O idioma da página está indicado no HTML
sim() não(x)
Com o uso do react native, o dispositivo do usuário usa, por padrão, o idioma nas configurações do dispositivo para a leitura e o srceen-reader conseguirá identificar elementos alternativos e textuais.

3- O site funciona com as imagens desativadas
sim(x) não()
As imagens são apenas para uma identificação visual de postagens, fotos de perfil ou logos, mas o aplicativo constinua navegável e funcional sem imagens. Essa opção de acessibildiade inclui dispositivos mais antigos ou com imagens desativadas por padrão do usuário, afim de que todos consigam utilizar. A visibilidade das imagens é, por sua vez, opcional

4- O site é legível e navegável com o CSS desativado
sim() não(x)
React Native renderiza componentes nativos para plataformas como iOS e Android, o que não se aplica na checklist. A opção de acessiblidade é configurada pelo próprio despositivo.

5- O site é legível aumentando o texto 2 vezes
sim(x) não()
Atualmente, não está implementada a funcionalidade no aplicativo. Entretanto, como o público-alvo do projeto inclui pessoas com deficiência visual e até mesmo idosos que, pela idade, muitos já não enxergam letras de fontes pequenas. Por esse motivo, é justo adaptar para que haja uma opção de aumento da fonte.

6- As tabelas têm headings <th> definidos
sim(x) não() 
A aplicação, por ser pensada em mobile utilizando react native, utilizará propriedades como  FlatList e a estilização via StyleSheet. É justo criar tabelas que seja acessível e bem estruturada para screen readers, garantindo que os dados sejam lidos corretamente, assim, garantindo a melhor experiência do usuário, para que seja bem delimitado e visível as tabelas.

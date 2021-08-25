# reagir-elástico-carrossel
Um componente de carrossel flexível e responsivo para reagir

# Por que precisamos de mais um componente de carrossel
Suporte a redimensionamento de elemento (capacidade de resposta verdadeira)
A maioria dos componentes do carrossel respondem ao tamanho da janela de visualização, mas este não é um suporte responsivo real, pois podemos ter um elemento com um width:500pxem uma 1200pxtela, a maioria dos componentes do carrossel "pensará" que estamos em um 1200pxmodo porque eles "observam" o tamanho da porta de visualização e não o tamanho do elemento de empacotamento. Este é o motivo pelo qual react-eleastic-carouselestá usando o observador de redimensionamento que nos dá um verdadeiro suporte responsivo, não importa o tamanho da tela que estamos.


Suporte a RTL (da direita para a esquerda) O suporte a idiomas da direita para a esquerda requer um suporte completo para renderização e animações da direita para a esquerda, o que não é compatível com a maioria dos componentes do carrossel. além disso, o suporte da direita para a esquerda é importante e deve ser um padrão para a maioria dos aplicativos .

# Pesquisas
https://www.npmjs.com/package/react-elastic-carousel

https://sag1v.github.io/react-elastic-carousel/


# Instalar
npm install --save react-elastic-carousel
ou
yarn add react-elastic-carousel

# Observação
react-elastic-carouselestá usando componentes estilizados para estilizar, isso significa que você também deve instalá-lo:
npm install --save styled-components

# Link do projeto
npm rum build
Foi gerado uma pasta com o nome build, está pasta serve para fazer uma url 
na plataforma netlify

https://carrossel-react-js.netlify.app/


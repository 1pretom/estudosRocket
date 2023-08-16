# Documentação

- [Documentação da Rocketseat](https://react-native.rocketseat.dev/)
- [Documentação oficial](https://reactnative.dev/)
(Esteja sempre acessando a documentação pois ela recebe atualizações)

- [Documentação expo](https://docs.expo.dev/)

utilizando npx não precisa ter o expo instalado na maquina
sem npx, utiliza o da minha máquina

npx expo start - para iniciar um projeto

formas de conectar
lan - no dispositivo fisico roda
local - no proprio pc com emulador
tunel - redes publicas

### Funcionamento do React Native

##### Abordagem tradicional no mobile em android e ios
no Android vai desenvolver utilizando Java / kotlin e gerar um .apk
no iOS vai desenvolver utilizando Object-C / Swift e gerar um .ipa
Isso aumenta a complexidade por ter que desenvolver duas vezes. Uma vez para cada ambiente.

##### Abordagem cross plataform do React Native
A base de código é desenolvida em Javascrpit
A complexidade é diminuida por ser uma base só, ó código passa por um processo de empacotamento gerando um Bundle que vai ter como destino o iOS ou o Android
O JSX é a sintaxe que utilizamos para desenvolver as interfaces de forma declarativa 

### O que é o JSX?
é a sintaxe que o react utiliza para criar interfaces de maneira declarativa
react native utiliza o react
o react tem o objetivo de criar interfaces
o react native trabalha específicamente com o contexto mobile

### Logbox
na cor amarela não quebra o app, mas fica o aviso
na cor vermelha quebra o app

### Etilizar elementos
dentro do elemento colocar style e chaves, e usar camelCase para dar nome aos elementos invés de separar por '-'

### Densidade de Pixel
É o número total de Pixel que existe dentro de uma área física da tela, (PPI - pixels per inch, ou pixel por polegada)
Existe a diferença entre pixel de hardware que é o ponto de luz na tela. E o pixel de software que é dinamico de acordo coma densidade de pixels da tela.
Quanto maior a densidade de pixels, mais detalhes é possível de visualizar
Por causa disso foi criada a Independência de Densidade, que renderiza os elementos de uma forma independente das caracteristicas e densidades de cada dispositivo. Android - DPI ('dots per inch', ou 'pontos por polegada') e iOS (points)

### Outra maneira de estilizar
Importar stylesheet no projeto e fazer uma const
const styles = StyleSheet.create ({
    estilização aqui
})


### Export e Export Default
No export default ele exporta sem precisar de chaves na importação
no export, precisa de chaves para especificar o que vai ser importado.
É possível combinar os 2 no mesmo import
no App.tsx necessariamente precisa ser export default, nos outros não
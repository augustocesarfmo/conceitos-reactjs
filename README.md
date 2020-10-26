# Conceitos do ReactJS

Esta aplicação reforça os conhecimentos básicos para construção de uma aplicação front-end utilizando o _framework_ ReactJS.

Entre os conhecimentos obtidos, pode-se destacar a importância da correta utilização dos seguintes plugins:

| Plugin  | Descrição                                                                                             |
| ------- | ----------------------------------------------------------------------------------------------------- |
| Babel   | Utilizado para converter/transpilar o código React para um código que o _browser_ entenda.     |
| Webpack | Para cada tipo de arquivo (.js, .css, .png etc) converte/transpila o código de uma maneira diferente. |

Também, foi possível revisar os conceitos mais importantes do React:

| Conceito               | Descrição                                                                                                                                                                                                                                                                                                     |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Componente             | Permite você dividir a _User Interface_ (UI) em partes independentes, reutilizáveis e pensar em cada parte isoladamente. Conceitualmente, componentes são como funções JavaScript. Eles aceitam entradas arbitrárias (chamadas "props") e retornam elementos React que descrevem o que deve aparecer na tela. |
| Propriedade            | Informações que você pode passar de um componente pai para um componente filho. Observação: Independente da declaração de um componente, como uma função ou uma classe, nuca se deve modificar suas próprias propriedades.                                                                                    |
| Estado & Imutabilidade | O estado armazena/controla as informações que podem ser exibidas na UI. O estado em si é imutável, ou seja, para realizar alterações em tela é necessário recriar o estado baseado nas informações anteriores.                                                                                                |

## Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [ReactJS](https://reactjs.org)
- [Axios](https://github.com/axios/axios)
- [VS Code][vc]

## Executando

Para clonar e executar este aplicativo, você precisará de [Git](https://git-scm.com), [Node.js v12.13][nodejs] ou superior + [Yarn v1.19][yarn] ou superior instalado no seu computador.

Na sua linha de comando execute:

```bash
# Clonando este repositório
$ git clone https://github.com/augustocesarfmo/conceitos-reactjs

# Acessando o repositório
$ cd conceitos-reactjs

# Instalando as dependências
$ yarn install

# Executando o app
$ yarn start
```

## 📝 Licença

Este projeto está sob a licença MIT. Consulte a [LICENÇA](https://github.com/fradeneto/devradar-mobile/blob/master/LICENSE) para obter mais informações.

---

by Augusto César

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/

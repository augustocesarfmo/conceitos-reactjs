# <span id="head1">Conceitos do ReactJS</span>

Esta aplicação reforça os conhecimentos básicos para construção de uma aplicação *front-end* utilizando o _framework_ ReactJS.

- [Conceitos do ReactJS](#head1)
	- [📚 Conceitos mais importantes do React](#head4)
	- [🚀 Tecnologias](#head5)
	- [ℹ️ Executando](#head6)
	- [📝 Licença](#head7)

### <span id="head4">📚 Conceitos mais importantes do React</span>
| Conceito               | Descrição                                                                                                                                                                                                                                                                                                     |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Componente             | Permite você dividir a _User Interface_ (UI) em partes independentes, reutilizáveis e pensar em cada parte isoladamente. Conceitualmente, componentes são como funções JavaScript. Eles aceitam entradas arbitrárias (chamadas "props") e retornam elementos React que descrevem o que deve aparecer na tela. |
| Propriedade            | Informações que você pode passar de um componente pai para um componente filho. Observação: Independente da declaração de um componente, como uma função ou uma classe, nuca se deve modificar suas próprias propriedades.                                                                                    |
| Estado & Imutabilidade | O estado armazena/controla as informações que podem ser exibidas na UI. O estado em si é imutável, ou seja, para realizar alterações em tela é necessário recriar o estado baseado nas informações anteriores.                                                                                                |

## <span id="head5">🚀 Tecnologias</span>

Este projeto foi desenvolvido com as seguintes tecnologias:

- [reactjs](https://reactjs.org)
- [axios](https://github.com/axios/axios)
- [vs code][vc]

## <span id="head6">ℹ️ Executando</span>

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

## <span id="head7">📝 Licença</span>

Este projeto está sob a licença MIT. Consulte a [LICENÇA](https://github.com/fradeneto/devradar-mobile/blob/master/LICENSE) para obter mais informações.

---

by Augusto César Oliveira 👐🏼

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/

# Danki Frontend - Projeto 08

Landing page responsiva desenvolvida durante o **Projeto 08** do curso de Frontend da [Danki Code](https://cursos.dankicode.com/). O exercício reúne HTML, CSS e componentes do Bootstrap em uma página de apresentação com navegação, seção institucional, diferenciais, inscrição em lista, contato e rodapé.

> **Status:** projeto de estudo, com conteúdo demonstrativo. Os formulários e os links da página ainda não estão conectados a um serviço de envio ou a um backend.

## Demonstração

A versão publicada está disponível no GitHub Pages:

[Acessar o projeto](https://lfbond.github.io/danki_frontend-pjt08/)

## Objetivos do projeto

- Praticar a estruturação de uma página completa com HTML5.
- Criar um layout adaptável para dispositivos móveis, tablets e desktops.
- Trabalhar com o sistema de grid e componentes do Bootstrap.
- Aplicar estilos próprios, imagem de fundo, sobreposição visual e espaçamentos com CSS.
- Exercitar componentes interativos, como menu responsivo e modal.
- Organizar arquivos estáticos de um projeto frontend sem etapa de build.

## Funcionalidades atuais

- Barra de navegação fixa com menu recolhível em telas menores.
- Seção inicial com imagem de fundo e chamada de apresentação.
- Seção “Sobre” com modal “Minha História”.
- Bloco de diferenciais com ícones do Font Awesome.
- Formulários visuais para inscrição em lista e contato.
- Rodapé com áreas para história, redes sociais e links úteis.
- Layout responsivo baseado nas classes de grid do Bootstrap.

Os formulários não possuem `action` nem integração com servidor. Ao abrir o projeto, eles devem ser tratados como parte visual da interface, e não como um fluxo de cadastro ou contato real.

## Tecnologias e dependências

- **HTML5** para marcação da página.
- **CSS3** para estilos, responsividade, imagem de fundo e composição visual.
- **Bootstrap 4.0.0-beta** carregado via CDN.
- **jQuery Slim 3.2.1** carregado via CDN para os componentes do Bootstrap.
- **Popper.js 1.11.0** carregado via CDN para posicionamento de componentes.
- **Font Awesome** mantido localmente em `css/` e `fonts/`.
- **GitHub Pages** como opção de publicação da página estática.

Não é necessário instalar Node.js, npm ou outras ferramentas de build para executar a versão atual.

## Pré-requisitos

- Um navegador moderno, como Chrome, Edge, Firefox ou Safari.
- Internet para carregar Bootstrap, jQuery e Popper.js pelos CDNs definidos em `index.html`.

## Como executar localmente

### Com Git

```bash
git clone https://github.com/lfbond/danki_frontend-pjt08.git
cd danki_frontend-pjt08
```

Depois, abra `index.html` no navegador. No Windows, também é possível abrir o arquivo diretamente pelo Explorador de Arquivos.

### Com um servidor local

Servir os arquivos por HTTP aproxima o ambiente local de uma publicação real. Com Python instalado, execute na pasta do projeto:

```bash
python -m http.server 8000
```

Em seguida, acesse [http://localhost:8000](http://localhost:8000).

Também é possível usar a extensão **Live Server** no VS Code para recarregar a página automaticamente durante o desenvolvimento.

## Estrutura de pastas

```text
.
├── index.html              # Página principal e conteúdo da landing page
├── css/
│   ├── style.css           # Estilos personalizados do projeto
│   ├── font-awesome.css    # Folha de estilos do Font Awesome
│   └── font-awesome.min.css
├── fonts/                  # Arquivos de fonte usados pelos ícones
└── images/
    └── bg.jpg              # Imagem de fundo da seção inicial
```

## Pontos de atenção

- Os recursos externos possuem versões antigas, mantidas para preservar o exercício original.
- A página utiliza textos e links de exemplo, como “Lorem ipsum”, “Link 1” e redes sociais sem destino configurado.
- O envio dos formulários ainda precisa de uma API ou serviço de formulários.
- A página não possui um arquivo JavaScript próprio; o JavaScript utilizado vem das dependências do Bootstrap incluídas no HTML.
- Não há um arquivo `LICENSE` neste repositório no momento. Defina e inclua uma licença antes de declarar formalmente os termos de uso do código.

## Melhorias planejadas

- Substituir textos fictícios por conteúdo final e configurar os links de navegação.
- Conectar os formulários a um backend ou serviço de envio seguro.
- Atualizar Bootstrap, jQuery e Popper.js para versões suportadas, avaliando possíveis ajustes de compatibilidade.
- Adicionar validação e mensagens de sucesso ou erro aos formulários.
- Melhorar acessibilidade com rótulos, estados de foco, contraste e testes com teclado.
- Otimizar a imagem de fundo e os demais recursos estáticos para reduzir o tempo de carregamento.
- Adicionar testes manuais em diferentes tamanhos de tela e navegadores.

## Contribuição

Sugestões e correções são bem-vindas. Para contribuir:

1. Faça um fork do repositório.
2. Crie uma branch para sua alteração:

   ```bash
   git checkout -b minha-melhoria
   ```

3. Faça a alteração e verifique a página no navegador.
4. Envie um pull request descrevendo o que foi modificado.

## Capturas de tela

![Captura de Tela 82](https://user-images.githubusercontent.com/69223872/166531349-1c14579d-2095-4c6b-9058-db5f52b4ed8a.png)
![Captura de Tela 83](https://user-images.githubusercontent.com/69223872/166531429-1faf05b0-e396-405d-819d-3606a5789db9.png)
![Captura de Tela 84](https://user-images.githubusercontent.com/69223872/166531464-23fbddae-8028-48cf-a910-e6deb1f073b8.png)

## Créditos

Projeto desenvolvido como parte dos estudos de Frontend da Danki Code. A folha de ícones utilizada é o Font Awesome, e os componentes de interface são fornecidos pelo Bootstrap.



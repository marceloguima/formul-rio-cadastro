Este repositório contém a implementação de um formulário de cadastro responsivo, construído com HTML e CSS. O objetivo é criar uma interface de usuário limpa e intuitiva para coletar dados de usuários.

Arquivos do Projeto:
index.html: Contém a estrutura HTML do formulário, incluindo todos os campos de entrada (nome, email, telefone, data de nascimento, senha, confirmação de senha, sexo) e o botão de envio.

style.css: Define o estilo visual do formulário, incluindo layout, cores, tipografia e responsividade.

Estrutura e Funcionamento:
index.html: Base da Aplicação
O arquivo HTML é a base estrutural do formulário. Ele utiliza os seguintes elementos e conceitos:

HTML5 Semântico: Utilização de tags HTML5 para organizar o conteúdo de forma lógica e acessível, como <header>, <main>, <form>, <label>, <input>.

Formulário (<form>):

O formulário agrupa os campos de entrada, cada um com um rótulo (<label>) correspondente.

Os atributos type, id, placeholder e required são usados para definir o tipo de entrada, associar rótulos aos campos, fornecer dicas de uso e garantir o preenchimento obrigatório.

Ícones (Font Awesome): Os ícones foram adicionados usando a biblioteca Font Awesome, melhorando a experiência visual e a usabilidade.

Campos de Entrada:

Tipos de Entrada: Utilização de tipos de entrada adequados (text, email, number, date, password, radio) para coleta de informações específicas.

Grupo de Rádio: A opção de sexo utiliza botões de rádio com o mesmo name para garantir a seleção de apenas uma opção.

Link para Login: Um link discreto para a página de login para usuários já cadastrados.

Botão de Envio (<button>): Um botão para a submissão do formulário.

style.css: Estilização e Responsividade
O arquivo CSS é responsável pelo visual do formulário, usando seletores CSS para estilizar os elementos. Os principais aspectos incluem:

Reset CSS: Utilização de um reset básico para remover estilos padrão do navegador e garantir um comportamento consistente entre diferentes navegadores.

Layout Flexível:

Utilização do modelo de layout flexbox para centralizar o formulário na tela e organizar os elementos dentro do formulário.

O container principal usa display: flex; com justify-content: center; e align-items: center; para centralizar o formulário.

Estilização dos Campos de Entrada:

Cada campo tem um estilo personalizado com bordas arredondadas, padding, e focus.

Os ícones são posicionados dentro dos campos.

Botão:

O botão é estilizado para ser visualmente atraente, com efeitos de hover.

Responsividade: O layout do formulário se adapta a diferentes tamanhos de tela, garantindo uma boa experiência de uso em dispositivos móveis e desktops (embora em um nível básico).

Próximos Passos do Desenvolvimento:
Implementação da Validação com JavaScript: Atualmente, o formulário é estático. Meu próximo passo é implementar a validação com JavaScript para garantir a integridade dos dados, incluindo verificação de formato (como email), confirmação de senha e campos obrigatórios.

Como Executar:
Clone este repositório: git clone <URL_DO_REPOSITORIO>

Abra o arquivo index.html em seu navegador.

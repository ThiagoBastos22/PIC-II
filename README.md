const historiasDeUsuario = [
    {
        id: 1,
        titulo: "Navegar por diferentes opções de cupcakes",
        requerente: "Usuário Final",
        acao: "Como um usuário, quero navegar por diferentes opções de cupcakes para escolher meus favoritos.",
        comentarios: "A experiência de navegação deve ser intuitiva e rápida, permitindo ao usuário explorar os cupcakes facilmente.",
        criteriosDeAceitacao: [
            "O usuário deve ver uma lista de cupcakes ao abrir o aplicativo.",
            "O usuário deve poder filtrar cupcakes por sabor, design e preço.",
            "O sistema deve exibir os cupcakes disponíveis dentro de um prazo de 2 segundos."
        ],
        regrasDeNegocio: [
            "Todos os cupcakes disponíveis devem ser listados.",
            "O filtro por sabor, design e preço deve funcionar de forma independente e sem sobrecarregar o aplicativo."
        ],
        requisitosNaoFuncionais: [
            "A lista de cupcakes deve ser carregada em menos de 2 segundos, mesmo com grandes volumes de dados."
        ],
        prioridade: 1,
        pontosDeHistoria: 5
    },
    {
        id: 2,
        titulo: "Personalizar o sabor e o design dos cupcakes",
        requerente: "Usuário Final",
        acao: "Como um usuário, quero personalizar o sabor e o design dos cupcakes para eventos especiais.",
        comentarios: "A personalização deve ser fácil e oferecer uma prévia realista do cupcake final.",
        criteriosDeAceitacao: [
            "O usuário deve poder selecionar sabores, coberturas e decorações.",
            "O usuário deve visualizar uma prévia do cupcake personalizado em tempo real.",
            "O sistema deve validar as combinações de sabores e decorações antes de permitir a confirmação."
        ],
        regrasDeNegocio: [
            "Apenas cópias válidas de sabores e decorações devem ser permitidas.",
            "O sistema deve apresentar sugestões fundamentadas na popularidade dos itens combinados."
        ],
        requisitosNaoFuncionais: [
            "A prévia do cupcake deve ser atualizada em tempo real.",
            "A personalização deve ser compartilhada de forma fluida, sem travamentos ou lentidão."
        ],
        prioridade: 1,
        pontosDeHistoria: 8
    },
    {
        id: 3,
        titulo: "Agendar a entrega dos cupcakes",
        requerente: "Usuário",
        acao: "Como um usuário, quero agendar a entrega dos cupcakes para garantir que receba-os na data correta.",
        comentarios: "O agendamento deve ser flexível e permitir ao usuário selecionar a data e o horário mais conveniente para ele.",
        criteriosDeAceitacao: [
            "O usuário deve poder selecionar a data e a hora da entrega.",
            "O usuário deverá receber uma confirmação do agendamento via e-mail ou notificação no app.",
            "O sistema deve validar a disponibilidade da localização escolhida."
        ],
        regrasDeNegocio: [
            "A data e hora de entrega devem ser verificadas para disponibilidade.",
            "Caso a data e hora selecionadas não estejam disponíveis, o usuário deve ser notificado com opções alternativas."
        ],
        requisitosNaoFuncionais: [
            "O agendamento deve ser processado em menos de 2 segundos.",
            "O sistema deve garantir que as mudanças de planejamento sejam refletidas imediatamente em todas as interfaces."
        ],
        prioridade: 1,
        pontosDeHistoria: 5
    },
    {
        id: 4,
        titulo: "Receber notificações sobre o status do pedido",
        requerente: "Usuário",
        acao: "Como um usuário, quero receber notificações sobre o status do meu pedido para saber quando for entregue.",
        comentarios: "As notificações devem ser claras e informativas, abrangendo todas as etapas do processo de compra até a entrega.",
        criteriosDeAceitacao: [
            "O usuário deve receber notificações em tempo real sobre o status do pedido.",
            "As notificações devem incluir informações claras sobre cada etapa do processo."
        ],
        regrasDeNegocio: [
            "As notificações devem ser enviadas para cada mudança de status do pedido.",
            "O usuário deve poder configurar preferências de notificações (ex: ativar/desativar notificações de status)."
        ],
        requisitosNaoFuncionais: [
            "As notificações devem ser enviadas em menos de 1 segundo após a mudança de status.",
            "As notificações devem ser compatíveis com os sistemas de iOS e Android."
        ],
        prioridade: 1,
        pontosDeHistoria: 5
    },
    {
        id: 5,
        titulo: "Adicionar cupcakes ao carrinho de compras",
        requerente: "Usuário",
        acao: "Como um usuário, quero adicionar cupcakes ao carrinho de compras para revisar minha seleção antes de finalizar a compra.",
        comentarios: "O carrinho deve ser intuitivo e permitir fácil adição e remoção de itens, com um total atualizado em tempo real.",
        criteriosDeAceitacao: [
            "O usuário deve poder adicionar e remover cupcakes do carrinho.",
            "O usuário deve visualizar o total atualizado no carrinho em tempo real.",
            "O carrinho deve exibir uma lista clara e organizada dos itens selecionados."
        ],
        regrasDeNegocio: [
            "O carrinho deve manter a seleção do usuário até a finalização da compra.",
            "O sistema deve verificar a disponibilidade dos cupcakes no carrinho antes da finalização."
        ],
        requisitosNaoFuncionais: [
            "O carrinho deve atualizar em tempo real ao adicionar ou remover itens.",
            "O tempo de resposta do carrinho não deve exceder 1 segundo."
        ],
        prioridade: 1,
        pontosDeHistoria: 5
    },
    {
        id: 6,
        titulo: "Finalizar compra",
        requerente: "Usuário Final",
        acao: "Como um usuário, quero finalizar a compra dos cupcakes para completar meu pedido.",
        comentarios: "A finalização da compra deve ser segura e rápida, garantindo que todos os detalhes estejam corretos antes da confirmação.",
        criteriosDeAceitacao: [
            "O usuário deve poder revisar o pedido antes de finalizar.",
            "O usuário deve receber uma confirmação de pedido após a compra.",
            "O sistema deve garantir que todos os dados do usuário (endereço, forma de pagamento) sejam corretos."
        ],
        regrasDeNegocio: [
            "O sistema deve verificar a disponibilidade de cupcakes antes de confirmar o pedido.",
            "O pagamento deve ser validado antes de concluir a compra."
        ],
        requisitosNaoFuncionais: [
            "A finalização da compra deve ser processada em menos de 3 segundos.",
            "A transação deve ser segura, usando criptografia para proteger os dados financeiros."
        ],
        prioridade: 1,
        pontosDeHistoria: 8
    },
    {
        id: 7,
        titulo: "Visualizar avaliações e comentários",
        requerente: "Usuário",
        acao: "Como um usuário, quero visualizar avaliações e comentários sobre os cupcakes para tomar uma decisão informada.",
        comentarios: "As avaliações devem ser desenvolvidas e ajudar o usuário a escolher os melhores cupcakes com base em experiências de outros clientes.",
        criteriosDeAceitacao: [
            "O usuário deve ver avaliações e comentários de outros usuários.",
            "As avaliações devem ser ordenadas por relevância ou dados."
        ],
        regrasDeNegocio: [
            "Somente consultas verificadas devem ser exibidas."
        ],
        requisitosNaoFuncionais: [
            "As avaliações devem carregar em menos de 2 segundos.",
            "O sistema deve garantir a integridade dos dados das avaliações."
        ],
        prioridade: 2,
        pontosDeHistoria: 3
    },
    {
        id: 8,
        titulo: "Acessar promoções e descontos exclusivos",
        requerente: "Usuário",
        acao: "Como um usuário, quero acessar promoções e descontos exclusivos para economizar nas minhas compras de cupcakes.",
        comentarios: "Oferecer promoções e descontos pode aumentar a fidelidade do cliente e incentivar compras recorrentes.",
        criteriosDeAceitacao: [
            "O usuário deve ver uma lista de promoções ativas.",
            "O usuário deve poder aplicar descontos ao finalizar a compra."
        ],
        regrasDeNegocio: [
            "As promoções devem ser válidas apenas para usuários registrados."
        ],
        requisitosNaoFuncionais: [
            "As promoções devem ser aplicadas de forma rápida.",
            "O sistema deve garantir que as promoções não sejam aplicadas em compras inválidas."
        ],
        prioridade: 2,
        pontosDeHistoria: 3
    },
    {
        id: 9,
        titulo: "Criar conta de usuário",
        requerente: "Usuário Final",
        acao: "Como um usuário, quero criar uma conta para acessar o aplicativo de cupcakes.",
        comentarios: "A criação de conta deve ser simples e rápida.",
        criteriosDeAceitacao: [
            "O usuário deve preencher um formulário de cadastro.",
            "O usuário deve receber uma confirmação de criação de conta por e-mail."
        ],
        regrasDeNegocio: [
            "O e-mail deve ser verificado antes de concluir o cadastro."
        ],
        requisitosNaoFuncionais: [
            "O cadastro deve ser processado em menos de 2 segundos."
        ],
        prioridade: 2,
        pontosDeHistoria: 3
    },
    {
        id: 10,
        titulo: "Redefinir senha",
        requerente: "Usuário",
        acao: "Como um usuário, quero redefinir minha senha caso a tenha esquecido.",
        comentarios: "A redefinição de senha deve ser rápida e segura.",
        criteriosDeAceitacao: [
            "O usuário deve poder solicitar a redefinição de senha.",
            "O usuário deve receber um link para redefinir a senha por e-mail."
        ],
        regrasDeNegocio: [
            "O link de redefinição de senha deve expirar após 24 horas."
        ],
        requisitosNaoFuncionais: [
            "O processo de redefinição deve ser concluído em menos de 2 minutos."
        ],
        prioridade: 1,
        pontosDeHistoria: 3
    },
    {
        id: 11,
        titulo: "Gerenciar favoritos",
        requerente: "Usuário",
        acao: "Como um usuário, quero adicionar cupcakes aos meus favoritos para poder visualizá-los facilmente depois.",
        comentarios: "A funcionalidade de favoritos deve ser fácil de usar e permitir o acesso rápido aos cupcakes preferidos.",
        criteriosDeAceitacao: [
            "O usuário deve poder adicionar e remover cupcakes dos favoritos.",
            "O usuário deve acessar seus cupcakes favoritos facilmente."
        ],
        regrasDeNegocio: [
            "A lista de favoritos deve ser mantida por tempo indeterminado até que o usuário escolha excluir."
        ],
        requisitosNaoFuncionais: [
            "O tempo de resposta ao adicionar ou remover favoritos deve ser menor que 1 segundo."
        ],
        prioridade: 2,
        pontosDeHistoria: 3
    },
    {
        id: 12,
        titulo: "Exibir cupcakes mais vendidos",
        requerente: "Usuário",
        acao: "Como um usuário, quero ver os cupcakes mais vendidos para ajudar em minha escolha.",
        comentarios: "Essa funcionalidade pode ajudar novos usuários a escolherem produtos populares.",
        criteriosDeAceitacao: [
            "O sistema deve exibir os cupcakes mais vendidos."
        ],
        regrasDeNegocio: [
            "Os cupcakes mais vendidos devem ser baseados em dados de vendas reais."
        ],
        requisitosNaoFuncionais: [
            "A lista de cupcakes mais vendidos deve ser carregada rapidamente."
        ],
        prioridade: 1,
        pontosDeHistoria: 2
    },
    {
        id: 13,
        titulo: "Suporte ao cliente",
        requerente: "Usuário",
        acao: "Como um usuário, quero entrar em contato com o suporte caso tenha problemas com meu pedido.",
        comentarios: "O suporte deve ser acessível e eficiente para resolver problemas de forma rápida.",
        criteriosDeAceitacao: [
            "O usuário deve ter acesso a um formulário de contato.",
            "O suporte deve responder ao usuário em um prazo de 24 horas."
        ],
        regrasDeNegocio: [
            "O suporte só deve responder a questões relacionadas a pedidos."
        ],
        requisitosNaoFuncionais: [
            "O tempo de resposta para a primeira resposta deve ser menor que 24 horas."
        ],
        prioridade: 2,
        pontosDeHistoria: 5
    },
    {
        id: 14,
        titulo: "Ver histórico de compras",
        requerente: "Usuário",
        acao: "Como um usuário, quero ver o histórico de minhas compras para acompanhar meu consumo.",
        comentarios: "O histórico de compras deve ser acessível a qualquer momento e permitir filtrar por data.",
        criteriosDeAceitacao: [
            "O usuário deve poder ver um histórico completo de compras.",
            "O usuário deve poder filtrar o histórico por data ou por tipo de produto."
        ],
        regrasDeNegocio: [
            "O histórico deve ser mantido por 1 ano."
        ],
        requisitosNaoFuncionais: [
            "O histórico de compras deve ser carregado rapidamente."
        ],
        prioridade: 2,
        pontosDeHistoria: 4
    },
    {
        id: 15,
        titulo: "Visualizar cupcakes por categoria",
        requerente: "Usuário",
        acao: "Como um usuário, quero visualizar cupcakes divididos por categoria para facilitar minha escolha.",
        comentarios: "A organização por categorias deve ser clara e permitir um filtro simples.",
        criteriosDeAceitacao: [
            "O usuário deve poder selecionar categorias como sabor, tamanho, ou design."
        ],
        regrasDeNegocio: [
            "As categorias devem ser baseadas nas informações de todos os cupcakes disponíveis."
        ],
        requisitosNaoFuncionais: [
            "As categorias devem carregar rapidamente."
        ],
        prioridade: 1,
        pontosDeHistoria: 3
    }
];

console.log(historiasDeUsuario);

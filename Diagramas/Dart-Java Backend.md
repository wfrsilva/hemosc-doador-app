# Dart-Java Backend
- Segregação de Perfil por Tipo de Usuário
- JWT com Role de perfil

- Autenticação
- -> Cadastro Usuário
  - Doador;
  - Operador;
  - Administrador;
- -> Login(*)

 - Usuários
 - -> Lista de usuários (Administrador)
 - -> Cadastro de usuários (Administrador)
 - -> Editar Usuários (Administrador)

 - Estabelecimentos (Hemocentros)
 -  -> Cadastro de Estabeleciomento (Administrador)
 -  -> Edistar Estabelecimento (Administrador)

 - Produtos (Material : Sangue, plaquetas)
 -  -> Cadatro de Produtos (Adm/Operador)
 -  -> Editar Produto (Adm/Operador)
 -  -> Listar Produtos p/ Estabelecimento (Adm/Operador)
 -  -> Detalhes do produto por ID (Adm/Operador)

 -  Doações
 -  -> Lista de doações por Estabelecimento (Adminitrador)
 -  -> Lista de doações por Produto do Estabelecimento 
 -  -> Lista de doações por Usuário

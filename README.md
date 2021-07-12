# Sistema de estoque e vendas - demo

Demonstração do gerenciamento de acessos do sistema (se o gif parar, atualize a página (F5)):

![Permissoes_demo](Permissoes_demo.gif)

Através de um usuário com as devidas permissões, é possivel adicionar novos usuários ao sistema, limitando seus acessos ao atribuir uma categoria ao mesmo.
Na categoria, define-se as permissões de leitura, cadastro, edição e exclusão de cada módulo do sistema.

No exemplo, o usuário (fictício) Lucas (que tem acesso a qualquer módulo (como mostrado)) cadastra um novo usuário (Ruan), posteriormente, cadastra uma nova categoria (que permite acesso apenas ao módulo de produtos, e apenas para leitura e edição). Essa categoria é atribuida ao usuário anteriormente cadastrado.

Ao logar com o usuário cadastrado, é possível verificar que o mesmo não tem acesso aos demais módulos, apenas ao que foi definido, e também só consegue editar os itens, ficando desabilitado os botões de criação e exclusão.

obs.: A categoria pode ser entendida como o cargo do usuário, dessa forma, todos usuários que tiverem o mesmo cargo, terão automáticamente os mesmos acessos.

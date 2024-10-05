# DIO - Segurança e Identidade na Azure
 Entendendo sobre Segurança e Identidade na Azure


## 🔎 Microsoft Entra ID	

Abra o portal da [`Azure`](https://portal.azure.com), e pesquise por **Microsoft Entra ID**.



Os usuários do ambiente on-premise podem ser replicados para a nuvem, porém os usuários da nuvem não podem ser replicados para o ambiente on-premise.

Observe as opções diponíveis no menu lateral:



Clique em **Users**:



Na próxima tela é possível verificar os usuários, o nome principal de cada usuário, o tipo de membros e se os usuários estão sincronizando de uma conta on-primesse ou não: 



No menu lateral, clique em **Sign-in logs**:



Neste item pode ser verificado de onde o usuário logou por último, qual o IP, o país e se o usuário logou pelo portal ou por alguma aplicação.

Clique na opção **Deleted users**, nesta página são listados os usuários deletados, e eles permanecem para consulta por até 30 dias, após esse período são excluídos permanentemente e de forma automática:



Os usuários deletados são mantidos por 30 dias, por segurança, caso seja necessário acessar a máquina do usuário para recuperar algum arquivo importante, a conta poderá ser restaurada.



Na opção **Password reset** é possível configurar para que os próprios usuários possam redefinir suas senhas caso esqueçam:



Volte ao topo do menu lateral e clique na opção **All users**, clique em **+ New user** e verifique que é possível criar um novo usuário ou convidar um usuário externo:


Clique em **Invite external user**:



Verifique as opções no cadastro de usuários externos:



Retorne e clique na opção **Create new user**:



Verifique as opções no cadastro de novos usuários e clique em **Next: Proparties**:




Na próxima tela clique em **Next: Assignments**:



Na opção **Bulk operations** é possível fazer o invite em grupo ou grande escala, sendo que o Azure já fornece o template em formato csv para download:



Volte ao menu **All services** do Microsoft Entra ID e clique em **Roles and administrators**:



Repare na mensagem de aviso de que para criar roles customizadas é necessário ter uma conta Premium:



Repare também nas opções de regras:



Volte ao menu **All services** do Microsoft Entra ID e clique em **Microsoft Entra Connect**:



Essa funcionalidade permite migrar os usuários do ambiente on-premise para a nuvem:



Clique na opção **Custom domain names**, essa opção permite customizar o domínio das contas do Azure:



A opção **Health** ainda está em preview e tem relação com o monitoramento do SLA:



## Permissões relacionadas à recursos




## Produtos Microsoft Entra ID

Clique no link *Azure Active Directory is now Microsoft Entra ID para ser direcionado à documentação:



Nessa documentação é explicada a mudança na nomenclatura do serviço:


Sendo que em relação aos serviços, para uma empresa o ideal é não utilizar a opção Free, pois ela não fornece muitas ferramentas.




## Links utilizados

- https://learn.microsoft.com/pt-br/entra/fundamentals/whatis

- https://learn.microsoft.com/pt-br/entra/fundamentals/new-name

- https://portal.azure.com/

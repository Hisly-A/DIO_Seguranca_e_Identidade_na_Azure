# DIO - Segurança e Identidade na Azure
 Entendendo sobre Segurança e Identidade na Azure


## 🔎 Microsoft Entra ID	

Abra o portal da [`Azure`](https://portal.azure.com), e pesquise por **Microsoft Entra ID**.

![AZ07-01](https://github.com/user-attachments/assets/872a0ca3-dc17-4486-9669-9b5be858f704)

![AZ07-02](https://github.com/user-attachments/assets/9750da70-9c11-463c-ad97-9ae36fbe1bb9)

Observe as opções diponíveis no menu lateral:

![AZ07-03](https://github.com/user-attachments/assets/3134e769-4e6d-43a2-8160-88fd91e4d6bb)

Clique em **Users**:

![AZ07-04](https://github.com/user-attachments/assets/7449bc17-37f6-44c9-903a-bd7a906ce6a9)

Na próxima tela é possível verificar os usuários, o nome principal de cada usuário, o tipo de membros e se os usuários estão sincronizando de uma conta on-primesse ou não: 

![AZ07-05](https://github.com/user-attachments/assets/57be4550-7b70-4e98-a789-fbe98ebe0905)

![AZ07-06](https://github.com/user-attachments/assets/40895cc2-5f2a-4412-ab11-780f297ff6b0)

No menu lateral, clique em **Sign-in logs**:

![AZ07-07](https://github.com/user-attachments/assets/b899af8c-fb65-444e-8990-deadce7e73ef)

Neste item pode ser verificado de onde o usuário logou por último, qual o IP, o país e se o usuário logou pelo portal ou por alguma aplicação.

Clique na opção **Deleted users**, nesta página são listados os usuários deletados, e eles permanecem para consulta por até 30 dias, após esse período são excluídos permanentemente e de forma automática:

![AZ07-08](https://github.com/user-attachments/assets/93d2173d-ca1a-4247-8407-d6ff6032b56a)

Os usuários deletados são mantidos por 30 dias, por segurança, caso seja necessário acessar a máquina do usuário para recuperar algum arquivo importante, a conta poderá ser restaurada.

Na opção **Password reset** é possível configurar para que os próprios usuários possam redefinir suas senhas caso esqueçam:

![AZ07-09](https://github.com/user-attachments/assets/86d636c0-c707-4c0f-905a-b45be5dbfbdd)

Volte ao topo do menu lateral e clique na opção **All users**, clique em **+ New user** e verifique que é possível criar um novo usuário ou convidar um usuário externo:

![AZ07-10](https://github.com/user-attachments/assets/8be8ef2a-5b24-462a-9820-ff18542e84fa)

Clique em **Invite external user**:

![AZ07-11](https://github.com/user-attachments/assets/6ee85295-931d-464b-8642-83e976b17a6f)

Verifique as opções no cadastro de usuários externos:

![AZ07-12](https://github.com/user-attachments/assets/0335d3d2-0837-4dcd-9e5b-b1a4efc33782)

Retorne e clique na opção **Create new user**:

![AZ07-13](https://github.com/user-attachments/assets/597aea61-50a2-40b6-9566-634c18c0def1)

Verifique as opções no cadastro de novos usuários e clique em **Next: Properties**:

![AZ07-14](https://github.com/user-attachments/assets/71072ad5-e971-463a-94f5-f9cd4db509ce)

Na próxima tela clique em **Next: Assignments**:

![AZ07-15](https://github.com/user-attachments/assets/4ce923b6-0daf-4b62-9b0a-e404f7ac6510)

![AZ07-16](https://github.com/user-attachments/assets/40bc9a15-20e9-4efd-b768-21088c8384f3)

Na opção **Bulk operations** é possível fazer o invite em grupo ou grande escala, sendo que o Azure já fornece o template em formato csv para download:

![AZ07-17](https://github.com/user-attachments/assets/5c77ed6b-75a5-4239-ac1b-8e9b329ee15d)

![AZ07-18](https://github.com/user-attachments/assets/535e179e-2b7f-4d72-a271-0a7723c157f3)

Volte ao menu **All services** do Microsoft Entra ID e clique em **Roles and administrators**:

![AZ07-21](https://github.com/user-attachments/assets/1231cedd-2340-420e-9b47-7b42327a8e38)

Repare na mensagem de aviso de que para criar roles customizadas é necessário ter uma conta Premium:

![AZ07-22](https://github.com/user-attachments/assets/095ab178-2eef-471d-9439-e7b82ae6f077)

Repare também nas opções de regras:

![AZ07-23](https://github.com/user-attachments/assets/9ec816f4-0475-4b42-8cf1-4a542dbdd4c2)

Volte ao menu **All services** do Microsoft Entra ID e clique em **Microsoft Entra Connect**:

![AZ07-24](https://github.com/user-attachments/assets/fbf3f3d7-63ff-447f-80e1-09d9cab9c813)

Essa funcionalidade permite migrar os usuários do ambiente on-premise para a nuvem:

![AZ07-25](https://github.com/user-attachments/assets/9a1ded40-9c4b-416b-b71e-05b1a62ebe69)

Um detalhe é que os usuários do ambiente on-premise podem ser replicados para a nuvem, porém os usuários da nuvem não podem ser replicados para o ambiente on-premise.

Clique na opção **Custom domain names**, essa opção permite customizar o domínio das contas do Azure:

![AZ07-26](https://github.com/user-attachments/assets/23eadffe-9a4c-495c-8708-83d9d33868c5)

A opção **Health** ainda está em preview e tem relação com o monitoramento do SLA:

![AZ07-27](https://github.com/user-attachments/assets/f66ce5ed-ee42-4789-8260-299da2bb2ebd)


## Produtos Microsoft Entra ID

Clique no link *Azure Active Directory is now Microsoft Entra ID* para ser direcionado à documentação:

![AZ07-19](https://github.com/user-attachments/assets/d5ca4618-32e9-49ea-b536-c262b8d015b8)

Nessa documentação é explicada a mudança na nomenclatura do serviço:

![AZ07-20](https://github.com/user-attachments/assets/821d208f-289a-4d49-bf3f-7143221ac83f)

Sendo que em relação aos serviços, para uma empresa o ideal é não utilizar a opção Free, pois ela não fornece muitas ferramentas.


## Permissões relacionadas à recursos

Acesse um grupo de recurso criado:

![AZ07-28](https://github.com/user-attachments/assets/eeb42ce9-cca2-4900-a705-d08589d88517)

Clique na opção **Access control (IAM)**:

![AZ07-29](https://github.com/user-attachments/assets/1519d13f-7d7b-4246-ab89-c933b7b8e213)

Clique em **View my access**:

![AZ07-30](https://github.com/user-attachments/assets/27ed7d14-afa9-4f93-8adb-7c650cf165ee)

Observe as opções disponíveis:

![AZ07-31](https://github.com/user-attachments/assets/64965967-dedb-476e-a4d3-b0731ccddd7e)

Para dar uma permissão para algum usuário no resource group, volte ao **Access control (IAM)** e clique na opção **Add role assignment**:

![AZ07-32](https://github.com/user-attachments/assets/7480df6f-8f2f-45d8-98f7-bcf4d69765a9)

Selecione as permissões necessárias e clique em **Next**:

![AZ07-33](https://github.com/user-attachments/assets/78ecb5e4-9ab9-46fd-b5e8-92e16ceb1d12)

Selecione para quem será dada a permissão e clique em **Next**:

![AZ07-34](https://github.com/user-attachments/assets/6da32cfb-6044-44d7-91d7-a905a01f3731)

A permissão dada será válida apenas para o resource group onde ela foi aplicada e não afetará os demais resources groups. Mas a permissão será válida para todos os recursos existentes dentro daquele resource group.

Da mesma forma também pode ser dada uma permissão granular para apenas um recurso dentro do resource group, como por exemplo nesta VNET existente no resource group:

![AZ07-35](https://github.com/user-attachments/assets/ac6d944f-ec6a-4fa4-a8d1-ad47ca73d5d2)

Note que ao acessar a VNET ela também possui a opção **Access control (IAM)**:

![AZ07-36](https://github.com/user-attachments/assets/f5d9d856-53a6-44cf-99bd-e6d8244a9ea0)


## Microsoft Defender for Cloud

No menu lateral do Azure pesquise por **Microsoft Defender for Cloud**:

![AZ07-37](https://github.com/user-attachments/assets/4acc0e0b-4901-427c-8ab5-79cfdd109992)

Esta funcionalidade é como um termômetro, pois traz uma análise de postura de segurança para mostrar quão bem ou ruim está a empresa:

![AZ07-38](https://github.com/user-attachments/assets/55fc022a-9a64-4212-b240-e6d386950b98)

Esta também é uma ferramenta multi cloud, por premitir se conectar à conta de outros cloud provider:

![AZ07-39](https://github.com/user-attachments/assets/fba7b63c-9656-476c-b194-b4a1106509d9)

![AZ07-40](https://github.com/user-attachments/assets/da079e5d-89a7-4b87-a9ba-b6c802f4ad68)

Ele traz as recomendações por meio de notas:

![AZ07-41](https://github.com/user-attachments/assets/e1537eb0-fa44-4809-8130-66c644c5ec5c)

O Microsoft Defender for Cloud também tem a parte de **DevOps Security**, permitindo se conectar às contas do GitHub, GitLab, AzureDevOps, entre outras, para serem monitoradas:

![AZ07-42](https://github.com/user-attachments/assets/6e20641d-d055-4e56-af57-f7fea6645b04)

![AZ07-43](https://github.com/user-attachments/assets/b1b08ace-4d8c-48db-acfb-72c4ed593a86)

Na opção **Security alerts** ficam os alertas de segurança, podendo ser configurados para serem enviados por e-mail:

![AZ07-44](https://github.com/user-attachments/assets/175450dc-8b13-4bd1-ac6c-c648f8d7968e)

Em **Settings**, **Defender plans**, ele traz a relação das máquinas e recursos monitorados e o valor cobrado pelo monitoramento de cada item:

![AZ07-45](https://github.com/user-attachments/assets/293cede8-5390-4968-ac11-28d07dae1482)

Sendo a opção **Foundational CSPM** a única gratuíta:

![AZ07-46](https://github.com/user-attachments/assets/1edbd04f-aa14-4fa2-bf15-71e65ad31dc5)

![AZ07-47](https://github.com/user-attachments/assets/f1c5001f-e706-405e-8c2c-08bf51923bc8)

As opções que não são contempladas pelo modelo **Foundational CSPM**, são contempladas pelo modelo **Defender CSPM**, porém possuem um custo:

![AZ07-48](https://github.com/user-attachments/assets/240630d4-25b4-4ee9-9692-e289fef8f611)


## Links utilizados

- https://learn.microsoft.com/pt-br/entra/fundamentals/whatis

- https://learn.microsoft.com/pt-br/entra/fundamentals/new-name

- https://portal.azure.com/

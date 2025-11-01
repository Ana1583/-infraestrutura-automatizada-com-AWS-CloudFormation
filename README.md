Desafio: Implementando Infraestrutura Automatizada com AWS CloudFormation
📖 Visão Geral

Este desafio, semelhante ao anterior, demonstra como utilizar o AWS CloudFormation para criar infraestrutura automatizada por meio da criação de Stacks.
A diferença em relação à aula é que os templates agora estão disponíveis via GitHub e não mais diretamente na página de criação de Stack da AWS.

Link para os templates oficiais: AWS CloudFormation Templates GitHub

https://github.com/aws-cloudformation/aws-cloudformation-templates

🛠️ Passo a Passo para Utilização dos Templates

Acessar o repositório GitHub:
![alt text](/Imagens/repositorio.png)

Navegar até a pasta CloudFormation.

Baixar o template desejado (.yaml ou .json).
![alt text](/Imagens/repositorioCloudFormation.png)

Criar uma Stack no AWS CloudFormation:

No Console AWS, vá para CloudFormation → Criar pilha.
![alt text](/Imagens/criarPilha.png)

Escolha Carregar um arquivo de modelo e selecione o template baixado.
![alt text](/Imagens/templatBaixado.png)

![alt text](/Imagens/criando.png)

Configurar e Criar a Pilha:

Informar o nome da pilha e preencher os parâmetros necessários (se houver).

Revisar e criar a Stack.

Após isso, o processo de criação é semelhante ao registrado no repositório: [AWSCloudFormation por belaems](https://github.com/belaems/AWSCloudFormation)

📌 Diferencial do Conteúdo das aulas foi a apresentação da diferença entre Terraform e AWS CloudFormation.

Comparação rápida: Terraform vs AWS CloudFormation.

Terraform → Multi-cloud, linguagem HCL, controle de estado local ou remoto.

CloudFormation → Exclusivo AWS, YAML/JSON, estado gerenciado pela AWS.

✅ Resultado Esperado

Ao finalizar a criação da Stack:

A infraestrutura definida no template estará provisionada automaticamente.

Você poderá acessar recursos como EC2, S3, Security Groups, dependendo do template escolhido.

📚 Observações

Este desafio é complementar ao anterior e recomenda-se realizar os exercícios apenas após consumir ambos os módulos, Terraform e CloudFormation, para melhor aproveitamento do aprendizado.

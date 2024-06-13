# EC2Proz

A banda de Miguel te contratou para ajudá-los na criação de uma instância EC2 para organizar a documentação e os arquivos importantes da banda. Recentemente, a banda se interessou pelo mundo da computação em nuvem e decidiu explorar o Amazon EC2, um serviço popular de infraestrutura como serviço (IaaS) oferecido pela Amazon Web Services (AWS). Eles também conheceram o Amazon Linux, que é uma distribuição otimizada para a nuvem, sendo uma opção excelente para as instâncias EC2. Os membros da banda estão empolgados para testar essa tecnologia e começar a armazenar e gerenciar os seus documentos e arquivos na nuvem. Neste exercício, iremos ajudá-los com isso.

1. Configuração da instância EC2
- acesse o Console da AWS e navegue até o serviço EC2; 
- crie uma nova instância EC2 usando a imagem Amazon Linux 2; 
- escolha o tipo de instância com base em suas necessidades de recursos. 

<img width="897" alt="acessoEC2_instancia_01" src="https://github.com/fritzgaldino/EC2Proz/assets/87190206/9fe539e2-c6fe-479d-94b8-d0e1119079e5">

2. Conexão via SSH
- após a instância ser criada, use a chave privada para conectar via SSH;
- execute os comandos necessários para acessar o terminal da instância.

<img width="502" alt="acessossh" src="https://github.com/fritzgaldino/EC2Proz/assets/87190206/1d4bd3dc-2f97-4f56-93bb-cd2cc059ba08">

3. Gerenciando o armazenamento
- explore as opções de armazenamento oferecidas pelo Amazon EC2; 
- crie um novo volume Elastic Block Store (EBS) com um tamanho de sua escolha; 
- anexe o volume à sua instância EC2.

<img width="895" alt="acessoEC2_volume_01" src="https://github.com/fritzgaldino/EC2Proz/assets/87190206/d106dd28-d382-4c67-a44c-09a2fe6e956a">

4. Formatando e montando o volume
- formate o volume recém-criado usando um sistema de arquivos de sua escolha;
- monte o volume em um diretório específico em sua instância.

<img width="614" alt="acessoEC2_armazenamento_04" src="https://github.com/fritzgaldino/EC2Proz/assets/87190206/17ffda24-bc6e-4db4-b3c6-c19c28527339">

5. Criação de arquivos
- crie um arquivo de texto simples usando o editor de sua preferência;
- salve esse arquivo no volume montado.

6. Explorando recursos:
- use comandos, como ls, df -h, mount e cat, para verificar o status do volume montado, o espaço em disco disponível e o conteúdo do arquivo criado

<img width="442" alt="exercicioEC2_01" src="https://github.com/fritzgaldino/EC2Proz/assets/87190206/f0aafa80-1590-443b-8907-5776d0d36270">

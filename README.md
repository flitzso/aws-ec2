# ☁️AWS-EC2 #

#### :round_pushpin:Use a região North Virginia ####
![north virginia](https://github.com/flitzso/aws-ec2/assets/106411702/3dc21d77-a774-440e-9b93-d7bd4b3095e0)

#### :round_pushpin:Selecione o modelo EC2 ####
![ec2 virtual machine](https://github.com/flitzso/aws-ec2/assets/106411702/62a8d5c4-db8f-4c79-9188-77cef74ce125)

#### :round_pushpin:No menu no canto esquerdo vá em Instancia -> Instancia ####
![instance](https://github.com/flitzso/aws-ec2/assets/106411702/ec78f56b-3b34-4e94-9d43-e51f8084bed8)

#### :round_pushpin:Checar se o filtro de instancia esta desligado ####
![filtro](https://github.com/flitzso/aws-ec2/assets/106411702/bfb97d3f-f768-4385-8c58-6d356da9785e)

#### :round_pushpin:Clique no botão Launch Instance [Executar instancias] ####

![launch](https://github.com/flitzso/aws-ec2/assets/106411702/87f470bf-d163-42d0-900c-52c3ea91be61)

#### :round_pushpin:Coloque o nome no server em Name and tags [depois que tiver experiencia pode adcionar mais tags] ####
![nameeeee](https://github.com/flitzso/aws-ec2/assets/106411702/db3321a3-2928-42ff-8a5c-b05ba8824786)

#### :round_pushpin:Application and OS Images (Amazon Machine Image) [vai escolher o seu] [eu escolhi amazon linux 2023 AMI] ####
![imgaaasss](https://github.com/flitzso/aws-ec2/assets/106411702/9f05f9f5-7987-443b-b785-f74af1b2821b)

#### :round_pushpin:Logo a baixo "Instance Type" vamos escolher a memoria, quantidade de cpu, escolhi t3.micro ####
![typeeee](https://github.com/flitzso/aws-ec2/assets/106411702/f0ec352e-8140-4548-b25c-dd35088fa3d0)

#### :round_pushpin:Key Pair(login) fica logo a baixo da instance type, vai em Create new key pair, preencha tudo, name, key pair type e o RSA, private key file format .ppk e para windows. ####
![keeeyyy](https://github.com/flitzso/aws-ec2/assets/106411702/179541f6-2c95-403b-9ff8-0a62df958047)

#### :round_pushpin:O arquivo com a key criptografada você tem que salvar em uma pasta importante ####
![keeyyyy](https://github.com/flitzso/aws-ec2/assets/106411702/259154af-2d49-44d6-976b-2bebf5c1df69)

#### :round_pushpin:Atualise o key pair name e escolha a que você criou ####
![keyaaaaaaaaaa](https://github.com/flitzso/aws-ec2/assets/106411702/572ed0d9-ef82-49ec-9bfd-06c29aa87dd4)

#### Network Setting logo a baixo da key pair,vai em edit: ####
![editt](https://github.com/flitzso/aws-ec2/assets/106411702/556e8e49-63b5-4b63-acef-c381ffa54d8c)

##### Faça como esta na imagem ####
![server1](https://github.com/flitzso/aws-ec2/assets/106411702/af73d244-42b5-487d-a74f-03d84999d235) <br />

![tcp22](https://github.com/flitzso/aws-ec2/assets/106411702/0afb8e4b-2a33-4353-a194-e5a97ef024d2) <br />

![addsg](https://github.com/flitzso/aws-ec2/assets/106411702/7c155f44-35a4-4e31-ad66-7bc3a14a60f2) <br />

![ruless](https://github.com/flitzso/aws-ec2/assets/106411702/3d4329eb-5c19-4e2a-87f5-3a0767ea5f3c)

##### Storage ####
![storage](https://github.com/flitzso/aws-ec2/assets/106411702/f3af7185-fab8-4a91-a616-28cffe95144a)

#### Advanced Details ####
![dt01](https://github.com/flitzso/aws-ec2/assets/106411702/1c89c019-3228-4d63-baee-95ddeb528957) <br />
![dt02](https://github.com/flitzso/aws-ec2/assets/106411702/f811e967-83a5-42df-941c-d51bd519c0c1) <br />
![dt03](https://github.com/flitzso/aws-ec2/assets/106411702/2ad38718-b6fc-4a2b-9d29-0c567207d0e4) <br /> 
![edit04](https://github.com/flitzso/aws-ec2/assets/106411702/f5ed40b5-6335-4d12-b4a8-c4b007d9aaba) <br /> 
![dt05](https://github.com/flitzso/aws-ec2/assets/106411702/5aa78778-1b33-441a-8b18-f4c2a85439a5)

#### AmazonSSMManagedInstanceCore -> no fim da pagina click em next ####
![dt06](https://github.com/flitzso/aws-ec2/assets/106411702/7e1d1621-4ae0-4dfc-b04d-87feeb4d756c)

#### Name, Review and Create! ####
![dt07](https://github.com/flitzso/aws-ec2/assets/106411702/65c34739-f353-4743-8823-64232227fc28)
#### Modifique apenas a parte de imagem acima e vá ate o fim da pagina e click Create Role ####

#### De refresh no canto e escolha o acesso que foi criado ####

![dt8](https://github.com/flitzso/aws-ec2/assets/106411702/b95b29c2-a422-49d0-836a-30dd87920f33)

#### Siga preenchendo como na imagem ####
![dt9](https://github.com/flitzso/aws-ec2/assets/106411702/66adaf36-95e0-4aac-ac37-04a8716f2026) <br />
![dt10](https://github.com/flitzso/aws-ec2/assets/106411702/5c42a2d9-9879-4bb3-bd15-19e01d11f408)  <br />
![dt11](https://github.com/flitzso/aws-ec2/assets/106411702/b1f36c5e-ba12-4972-9a33-c9463bc7e5d1) <br />
![dt12](https://github.com/flitzso/aws-ec2/assets/106411702/1d2021bc-6386-488b-8d67-e811a72edbe1) <br />
![dt13](https://github.com/flitzso/aws-ec2/assets/106411702/8c3c7541-688b-47cd-9264-ded187fe8510) <br />
![dt14](https://github.com/flitzso/aws-ec2/assets/106411702/363e1a75-eba9-44b0-b37e-e3e530f649f3)

#### Role ate o fim da pagina e click no botão: ####
![dt15](https://github.com/flitzso/aws-ec2/assets/106411702/da48f153-318f-4440-8872-55c52372708c)

#### Copie e cole ####
![dt16](https://github.com/flitzso/aws-ec2/assets/106411702/39ac5285-dbe1-47fc-8400-e5a9dfa6a797)

#### Esta funcionando porem tem um detalhe para ser resolvido ####
![dt17](https://github.com/flitzso/aws-ec2/assets/106411702/ce2475f4-2dfb-44c4-85a4-be0fc9728e41)

#### Entrando no terminal AWS ####

![dt18](https://github.com/flitzso/aws-ec2/assets/106411702/08744910-8a06-42ac-ab7b-909ad3fc942d) <br />

![dt19](https://github.com/flitzso/aws-ec2/assets/106411702/7d99474c-62a4-41b6-9be3-fe19046ce5bb) <br />

![dt20](https://github.com/flitzso/aws-ec2/assets/106411702/afc6566d-f8d2-4e1f-8997-a84e9aa5e73d)

#### Como trocar o script e ou criar arquivo caso não exista ####
##### sudo su - #####
##### cd /var/www/html/ #####
##### ls  [pra visualisar arquivo] #####

#### Caso arquivo não exista faça isso ####
##### nano index.html  [vai abrir um edite pra você colocar sua frase]#####
##### Ctrl + x  [você sai] #####
##### Y        [escolha Y] #####
##### W        [Aperta enter e pronto] #####

#### Para editar um arquivo ja existente ####
##### vim index.html  [editar] #####
##### esc -> shift + : [coloque w aperte enter] #####
##### shift + : [digite Q aperte enter] para sair do vim #####
##### Só dar refresh na pagina e pronto #####
##### Fecharo terminal clique aqui #####
![dt21](https://github.com/flitzso/aws-ec2/assets/106411702/0b7b3b0f-e627-4710-9431-572db874c248)


### Deletar o Servidor [IMPORTANTE] ###
 ![dt22](https://github.com/flitzso/aws-ec2/assets/106411702/b592ee8c-b858-46c4-89c9-5dbb142067a9) <br />

![dt23](https://github.com/flitzso/aws-ec2/assets/106411702/094cca8e-52d0-4d41-97a2-8263ec4311ce) 


#### Pronto o servidor esta sendo deletado ####

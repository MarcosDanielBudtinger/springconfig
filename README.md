# springconfig

Projeto criado para fins de estudo de como trabalhar com profiles no springboot

O projeto tem apenas duas dependências, sendo a padrão WEB e a do LOMBOK.

No mesmo é possível trabalhar com dois profiles, um de DEV e outro de PROD.

Para rodar basta seguir os seguintes passos:
- Fazer clone do projeto.
- Alterar a primeira linha do arquivo application.properties para o profile desejado ex:
- `spring.profiles.active=prod para produção`
- `spring.profiles.active=dev para desenvolvimento`

-executar o projeto através da sua IDE preferida ou via terminal com o comando `spring-boot:run`

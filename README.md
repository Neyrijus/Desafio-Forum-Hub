# Desafio FórumHub – API REST

API REST em Spring Boot para gerenciamento de tópicos, usuários, cursos e respostas, com autenticação via JWT.

🚀 Tecnologias

Spring Boot • Spring Security • Spring Data JPA • MySQL • Flyway • Lombok • Swagger/OpenAPI • JWT

⚙️ Execução
git clone https://github.com/LuisBarrichello/Challenge-API-REST-ForumHub.git
cd forumhub
./mvnw spring-boot:run

🔑 Autenticação

POST /login → gera token JWT

Usar Authorization: Bearer <token> nas rotas protegidas

📌 Endpoints principais

Tópicos: GET/POST/PUT/DELETE /topics

Usuários: GET/POST/PUT/DELETE /users

Cursos: GET/POST/PUT/DELETE /courses

Respostas: GET/POST/PUT/DELETE /topics/{idTopic}/replies

📖 Documentação

Swagger disponível em:
http://localhost:8080/swagger-ui.html

# Personal Running Coach

Aplicativo de treinos personalizados para corrida, com integração à API do Strava e geração de treinos inteligentes via IA (Google Gemini).

## Funcionalidades

- Integração com a API do Strava para coletar corridas e perfil do usuário
- Geração de treinos semanais personalizados com base em metas e nível atual
- IA especializada responde com plano completo em JSON estruturado
- Backend robusto em .NET Core + Clean Architecture
- Frontend moderno com React
- Banco de dados com SQL Server

## Como funciona

1. O usuário conecta sua conta Strava.
2. O sistema coleta dados de treino e perfil físico.
3. A IA (via Gemini) recebe os dados e retorna um plano de treinos semanais até a meta final.
4. O plano é exibido no frontend de forma clara e organizada.

## Tecnologias utilizadas

- .NET Core (MVC, POO, Clean Architecture)
- Entity Framework + SQL Server
- React
- API do Strava
- Google Gemini API

## Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/Th1Ag011/NextRun.git


# Backend (.NET)
cd backend
dotnet restore
dotnet run

# Frontend (React)
cd frontend
npm install
npm start

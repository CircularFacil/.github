# 🚌 Circular Fácil

> **Uma plataforma inteligente para localização e previsão de chegadas de ônibus circulares em campi universitários**

O **Circular Fácil** é uma solução desenvolvida por estudantes da **Universidade Federal de Juiz de Fora (UFJF)** que revoluciona a experiência de transporte universitário. Nossa plataforma oferece localização em tempo real e previsões precisas de chegada dos ônibus circulares, facilitando o dia a dia de estudantes, professores e funcionários.

🎯 **Nosso objetivo** é criar uma ferramenta open-source que possa ser facilmente adaptada e implementada em qualquer campus universitário do Brasil.

<p align="center">
  <img src="./public/CircularFacilPassageiro.png" alt="Interface do Aplicativo Circular Fácil para Passageiros" width="350"/>
</p>
<p align="center"><em>Interface intuitiva do aplicativo para passageiros</em></p>

## 🏗️ Arquitetura do Sistema

Nossa plataforma é construída com uma **arquitetura moderna e escalável**, dividida em três componentes principais que trabalham em harmonia:

### 🔧 Backend
**Stack:** Node.js + Express.js  
**Função:** Coração do sistema que gerencia rotas, calcula previsões e fornece APIs

O servidor backend é responsável por processar dados de localização em tempo real, calcular previsões de chegada inteligentes e servir APIs robustas para os aplicativos frontend.

📁 **Repositório:** [CircularFacilBackend](https://github.com/CircularFacil/CircularFacilBackend)  
🌐 **Hospedagem:** Atualmente local com [ngrok](https://ngrok.com/) para exposição externa

### 📱 Frontend do Motorista  
**Stack:** Next.js + React  
**Função:** Interface dedicada para motoristas compartilharem localização

Aplicação web responsiva que permite aos motoristas:
- ✅ Identificar o veículo com ID único
- 📍 Compartilhar localização automaticamente
- ⚙️ Configurar intervalos de atualização personalizáveis

📁 **Repositório:** [CircularFacilMotorista](https://github.com/CircularFacil/CircularFacilMotorista)

### 🎯 Frontend do Passageiro
**Stack:** Next.js + React  
**Função:** Interface principal para estudantes e usuários finais

Aplicação intuitiva que oferece aos passageiros:
- 🗺️ Mapa interativo com pontos de parada
- ⏰ Previsões de chegada em tempo real  
- ⭐ Sistema de favoritos para pontos frequentes
- 📱 Interface otimizada para dispositivos móveis

📁 **Repositório:** [CircularFacil](https://github.com/CircularFacil/CircularFacil)

---

### 🚀 Como começar?

Cada repositório contém instruções detalhadas de instalação e configuração. Recomendamos começar pelo backend e depois configurar os frontends conforme sua necessidade.

---

## 🛠️ Tecnologias Utilizadas

### Backend
- **Node.js** - Runtime JavaScript
- **Express.js** - Framework web minimalista
- **ngrok** - Túnel para exposição de APIs locais

### Frontend
- **Next.js** - Framework React com SSR
- **React** - Biblioteca para interfaces de usuário
- **TypeScript** - JavaScript com tipagem estática
- **Leaflet** - Biblioteca para mapas interativos

### Ferramentas de Desenvolvimento
- **Git** - Controle de versão
- **GitHub** - Hospedagem de código e colaboração
- **Expo** - Ferramenta para desenvolvimento e teste de aplicativos React Native
- **pnpm** - Gerenciador de pacotes eficiente
- **npx** - Executor de pacotes Node.js


## 🤝 Como Contribuir

Adoramos receber contribuições da comunidade! Existem várias formas de ajudar o projeto:

### 🐛 Reportando Bugs
Encontrou um problema? Abra uma **issue** no repositório correspondente com:
- Descrição detalhada do problema
- Passos para reproduzir
- Capturas de tela (se aplicável)

### 💡 Sugerindo Melhorias  
Tem uma ideia incrível? Compartilhe conosco através de:
- **Issues** para discussões
- **Pull Requests** para implementações
- Aba **Projects** para acompanhar o roadmap

### 🛠️ Desenvolvendo
1. Faça um fork do repositório desejado
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

### 📞 Contato
Entre em contato com os mantenedores para discussões mais aprofundadas ou dúvidas sobre contribuições:

- **Lucas Chaves** - [GitHub](https://github.com/LucasVChaves) | [LinkedIn](https://www.linkedin.com/in/lucasvchaves/) | [Email](mailto:lucasvchaves@gmail.com)
- **Marcelo Rother** - [GitHub](https://github.com/MarceloRother) | [LinkedIn](https://www.linkedin.com/in/mrothersf/) | [Email](mailto:marcelorotherwork@gmail.com)
- **Iury Mendonça** - [GitHub](https://github.com/iiUrryy) | [LinkedIn](https://www.linkedin.com/in/iurymendonca/)

---

## 📄 Licença

Este projeto e todos os seus componentes estão sob licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

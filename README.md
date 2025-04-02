![minecraft_welcome](https://github.com/user-attachments/assets/8fccb0ea-812e-474a-be70-f2bbaab94b77)

<h1 align="center">GibasWelcomeMessage</h1>
<p align="center">
  Plugin de mensagens de boas-vindas personalizáveis para servidores Paper 1.21+
</p>

<p align="center">
  <a href="https://github.com/SeuUsuario/GibasPlugin/releases"><img src="https://img.shields.io/github/v/release/SeuUsuario/GibasPlugin?label=vers%C3%A3o&style=flat-square" alt="Release"></a>
  <a href="https://github.com/SeuUsuario/GibasPlugin/blob/main/LICENSE"><img src="https://img.shields.io/github/license/SeuUsuario/GibasPlugin?style=flat-square" alt="License"></a>
  <a href="https://github.com/SeuUsuario/GibasPlugin/stargazers"><img src="https://img.shields.io/github/stars/SeuUsuario/GibasPlugin?style=flat-square" alt="Stars"></a>
</p>

---

## ✨ Sobre o Plugin

O **GibasWelcomeMessage** traz uma recepção amigável e visualmente estilosa para jogadores ao entrarem no servidor. Com ele, você pode configurar mensagens de boas-vindas com variáveis, cores, emojis, e efeitos sonoros, tudo via `config.yml`.

---

## ⚙️ Funcionalidades

- ✅ Mensagens de entrada personalizáveis com cor e emojis
- 🔁 Variáveis dinâmicas como `%player%`, `%online%` e `%servidor%`
- 🔊 Som ao entrar (personalizável via nome do som)
- 🔄 Comando `/gibas reload` para recarregar a config sem reiniciar o plugin
- 🧩 Código limpo, leve e fácil de expandir

---

## 📦 Instalação

1. Baixe a versão mais recente na aba [Releases](https://github.com/SeuUsuario/GibasPlugin/releases)
2. Coloque o `.jar` na pasta `plugins` do seu servidor Paper 1.21+
3. Inicie ou reinicie o servidor
4. Edite o `config.yml` gerado para personalizar

---

## 📁 Exemplo de config.yml

```yaml
servidor: ServerTeste

welcome-messages:
  - "&6&m                                         "
  - "&e&l👋 BEM-VINDO(A) &f%player% &7ao &b%servidor%"
  - "&fEstamos felizes em te ver por aqui ☺"
  - "&a✔ Use &e/ajuda &apara ver os comandos."
  - "&b🌐 Canal: &9youtube.com/@GibasOficial"
  - "&6&m                                         "

welcome-sound:
  enabled: true
  sound: entity.player.levelup
  volume: 1.0
  pitch: 1.0

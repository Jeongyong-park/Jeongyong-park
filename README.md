### Hi there 👋
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fchisquare88%2Fhit-counter&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=%EB%B0%A9%EB%AC%B8%EC%9E%90%EC%88%98&edge_flat=false)](https://hits.seeyoufarm.com)


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=chisquare88&count_private=true&show_icons=true&theme=dark)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=chisquare88&theme=dark)](https://github.com/dokdogalmaegi/github-readme-stats)

<!--
**chisquare88/chisquare88** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```mermaid
sequenceDiagram
participant U as User
participant C as Client
participant S as Server
participant DB as Database

U ->> C: Fill username
U ->> C: Fill password
C ->> U: Enable "Login" button
U ->> C: Click "Login" button
C ->>+ S: POST /login
S ->>+ DB: SELECT FROM users
Note over S,DB: See login.py for impl. details
DB -->>- S: results
S -->>- C: { authenticated: true }
C ->> U: redirect /home
```

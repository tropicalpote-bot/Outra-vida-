# OUTRA VIDA 🎮

Simulador social de vida virtual — protótipo inicial jogável.

## Executar
Abra `index.html` no navegador ou publique como site estático na Vercel (framework: Other; diretório raiz; sem comando de build).

## MVP atual
- Criação de avatar e nome
- Apartamento interativo com movimento por toque, setas ou WASD
- Economia 100% virtual e profissões com salários e requisitos
- Cursos para desbloquear carreiras
- Energia, alimentação, felicidade, saúde e consequências
- Comer, dormir, estudar, socializar, atendimento e decoração
- Experiência, níveis, dias e salvamento local

**Importante:** esta versão não tem 3D real nem multiplayer. O cenário é uma primeira simulação visual em 2D. Não há autenticação ou banco online. Valores de moedas não são dinheiro real.

## Roadmap e checklist
### Fase 1 — Protótipo jogável
- [x] Interface responsiva e identidade inicial
- [x] Personagem, apartamento e movimentação
- [x] Necessidades, economia, trabalhos e cursos
- [x] Progressão e salvamento local
- [ ] Teste em celular e validação da diversão
- [ ] Assets autorais e animações 3D

### Fase 2 — Conta e multiplayer
- [ ] Supabase Auth (cadastro, login, recuperação)
- [ ] Banco de personagens, inventário e transações com RLS
- [ ] Economia validada no servidor (anti-trapaça)
- [ ] Cidade compartilhada e presença online
- [ ] Chat, amizade, bloqueio, denúncia e moderação
- [ ] Convites e grupos

### Fase 3 — Vida social
- [ ] Perfis, interesses e signos opcionais
- [ ] Relacionamentos consensuais e privacidade
- [ ] Casamento virtual, família e visitas
- [ ] Moradias, móveis, lojas e inventário

### Fase 4 — Economia avançada
- [ ] Emprego CLT virtual e contratos
- [ ] Empresas, funcionários e salários
- [ ] Cursos, profissões e progressão
- [ ] Mercado de produtos virtuais e impostos balanceados
- [ ] Prevenção de inflação e exploração de bugs

### Fase 5 — Produto comercial
- [ ] Painel de administração e telemetria
- [ ] Testes de carga e segurança
- [ ] PWA e versão Android
- [ ] Monetização cosmética opcional
- [ ] Políticas de privacidade, termos e classificação etária

## Conexões necessárias futuramente
Supabase para autenticação, dados e multiplayer; Vercel para deploy web; eventualmente serviço de tempo real dedicado. Nunca incluir chaves secretas no frontend.

## Atualização — Passo de polimento visual (15/10/2026)
- [x] Cidade recebeu praça pavimentada, bancos, canteiros floridos, postes, jardineiras e nuvens animadas.
- [x] Movimento com corrida (Shift), controles de câmera e interação por proximidade.
- [x] Colisão com deslizamento por paredes e comando "Destravar".
- [x] Editor de avatar local com cores, formatos e acessórios.
- [x] Validação sintática do JavaScript e confirmação de deploy READY na Vercel.
- [ ] Teste real no navegador de mesa e celular (não verificado automaticamente).
- [ ] Substituir personagem geométrico por personagem humano estilizado com esqueleto e animações naturais Idle/Walk/Run.
- [ ] Importar modelos 3D e cenário licenciados para uso comercial (preferir CC0).
- [ ] Melhorar câmera com colisão física, inércia, zoom e olhar ao redor por toque.
- [ ] Criar interiores reais das lojas e minijogos jogáveis.
- [ ] Persistência por conta no Supabase e validação da economia no servidor.

### Referências para assets legais
- Kenney Mini Characters: https://kenney.nl/assets/mini-characters — licença CC0 segundo o publicador.
- Kenney Animated Characters: https://kenney.nl/assets/animated-characters-protagonists — licença CC0 segundo o publicador.
- Kenney Mini Arcade: https://kenney-assets.itch.io/mini-arcade — licença CC0 segundo o publicador.

Não utilizar materiais extraídos de The Sims, Roblox, Habbo ou outros jogos sem autorização. A experiência visual ainda é **protótipo 3D**, não jogo premium final.

### Como testar esta versão
Abra https://outravida.vercel.app, inicie uma nova vida e personalize um avatar. Teste:
1. W/S/A/D e setas nas quatro direções; Shift para correr.
2. Girar a câmera com mouse, zoom pela roda, C para virar ângulo.
3. Encostar em prédios e deslizar em vez de ficar preso.
4. Botão "Destravar" para regressar à praça.
5. Interagir com os locais e observar alterações no saldo, necessidades e histórico.
6. Atualizar o navegador e conferir continuidade do progresso local.
7. No celular, tocar no joystick e no botão de interagir.

É necessário navegador com WebGL e acesso à biblioteca Three.js importada via CDN.

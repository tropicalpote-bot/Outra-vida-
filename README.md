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

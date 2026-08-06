# Plano de Negócios — Clube de Vegetais Orgânicos

**Modelo:** Clube de assinatura semanal de vegetais orgânicos, com fornecedores regionais entregando em um Centro de Distribuição (CD) próprio para separação, embalagem e delivery ao cliente final, respeitando a sazonalidade das safras.

**Data:** Agosto/2026
**Versão:** 1.1 — inclui pesquisa de mercado por capital, metodologia de fornecedores em 100km, análise de escalabilidade e veredito de viabilidade (documento vivo — revisar trimestralmente)

---

## 1. Sumário Executivo

O **Clube.org** é um serviço de assinatura recorrente que conecta pequenos e médios produtores orgânicos regionais a consumidores urbanos, entregando semanalmente uma cesta de vegetais, legumes e frutas frescas, organizada em torno da safra da estação (sazonalidade), com curadoria de qualidade feita em um CD próprio antes do delivery.

O diferencial não é só "vender orgânico" — é resolver três dores simultâneas:

- **Do consumidor:** confiança na origem/qualidade, comodidade (não precisa ir à feira), preço mais estável que orgânico de prateleira de supermercado.
- **Do produtor regional:** escoamento previsível da produção, sem depender só de feira/CEASA, com pagamento e planejamento de plantio antecipados.
- **Do mercado:** hoje a oferta é fragmentada entre feiras orgânicas (baixa conveniência), supermercados premium (preço alto, curadoria fraca) e grandes food-techs (foco em sortimento geral, não em orgânico/sazonalidade como proposta central).

O modelo de receita é uma **assinatura semanal ou quinzenal** (plano fixo com opção de pausa/skip e customização parcial de itens), complementada por venda avulsa via loja online para quem ainda não assina.

Este documento cobre: mercado, modelo de negócio, operação (fornecedores → CD → delivery), tecnologia (site, apps de gestão para fornecedor e cliente, pagamentos), marketing, estrutura de equipe, riscos e plano financeiro inicial.

---

## 2. Análise de Mercado

### 2.1 Panorama e tendências

*Dados de mercado (fontes: Organis, IBGE/PNAD Contínua, IMARC Group, MAPA/CNPO — ver seção 2.5 para lista completa de fontes).*

- O mercado brasileiro de alimentos orgânicos foi avaliado em **US$ 4,3 bilhões em 2025**, com projeção de chegar a **US$ 16,7 bilhões até 2034** (CAGR ~15,9% no período) segundo a IMARC Group — um crescimento estrutural, não um pico conjuntural.
- O volume de produção orgânica no Brasil cresceu **12% em relação ao ano anterior**, o maior índice já registrado (Organis).
- A penetração de consumo quase dobrou em 6 anos: **15% dos domicílios brasileiros tinham algum orgânico à mesa em 2017, contra 36% em 2023** (Organis) — ainda longe da saturação, o que sustenta a tese de espaço de crescimento.
- **Insight relevante para a escolha de mercado:** a penetração de consumo **não** é maior nas capitais mais ricas. Por região, o Nordeste lidera com 45% de penetração, seguido do Centro-Oeste com 42%, e o Sudeste (SP/RJ) vem **por último entre as regiões, com 30%**. Isso quebra a intuição óbvia de "começar em São Paulo por ser a maior e mais rica praça" — o Sudeste é onde a categoria, proporcionalmente, ainda penetrou menos.
- Preços de orgânicos in natura (verduras, legumes, frutas, ovos) caíram até 8% em média segundo o IBGE, ampliando o acesso a diferentes perfis de renda — bom para o TAM, mas também sinaliza pressão de preço estrutural no setor (ver seção 11 e 16).
- O canal de venda direta (assinatura, e-commerce, clubes) cresce mais rápido que o canal físico tradicional (feira, hortifruti), especialmente em capitais e regiões metropolitanas. O hábito de assinatura recorrente (clubes de vinho, café, beleza) já é familiar ao consumidor brasileiro, reduzindo a fricção de adoção do modelo "clube".
- Grandes redes de varejo (Pão de Açúcar, Carrefour, St Marche) têm ampliado gôndolas orgânicas, e apps de entrega geral (iFood Mercado, Rappi, Zé Delivery) também vendem hortifruti — **a ameaça competitiva de conveniência é real**, mas eles competem em sortimento amplo, não em curadoria + sazonalidade + relação direta com produtor.

### 2.2 Público-alvo

- **Perfil primário:** famílias classe A/B, 28–50 anos, já compram orgânico esporadicamente, valorizam saúde/tempo, moram em capitais ou grandes cidades com renda disponível para um ticket de R$ 70–180/semana.
- **Perfil secundário:** casais/famílias com filhos pequenos (motivação: introdução alimentar saudável) e pessoas com restrições alimentares/estilo de vida (vegetarianos, veganos, low-carb).
- **Comportamento:** já usam apps de delivery, valorizam conveniência, sensíveis a comunicação de propósito ("apoie o produtor local") e a conteúdo (receitas, dicas de conservação).

### 2.3 Concorrência

| Tipo | Exemplos de categoria | Força | Fraqueza |
|---|---|---|---|
| Feiras orgânicas | Feiras de bairro | Preço baixo, autenticidade | Baixa conveniência, sem recorrência estruturada |
| Clubes de assinatura de hortifruti | Players regionais de caixa orgânica | Modelo já validado, comunidade fiel | Escala pequena, operação manual, tech fraca |
| E-commerce/hortifruti online | Apps de entrega geral, hortifrutis com delivery próprio | Conveniência, sortimento amplo | Curadoria fraca, não é 100% orgânico, sem narrativa de sazonalidade/produtor |
| Supermercado premium | Redes com seção orgânica | Confiança de marca, ponto físico | Preço alto, produto às vezes não é tão fresco, zero relação direta com produtor |

**Concorrentes diretos identificados no Brasil (mapeamento de mercado, ago/2026):**

| Player | Praça | Modelo de preço observado |
|---|---|---|
| Flora Orgânicos | Brasília (DF) | A partir de R$ 26/entrega, escolha de quantidade |
| Clube Orgânico | Não regionalizado / múltiplas praças | R$ 45,95 – R$ 95,90/entrega, por tamanho de cesta |
| Clube +Q (Mais Quitanda) | Não regionalizado | R$ 54 – R$ 240/mês, por peso |
| Terra Forte Orgânicos | Não regionalizado | Assinatura semanal, frete grátis |
| Horti Clube (iFrutus) | São Paulo (SP) | 3 opções de cesta orgânica |
| Fungo de Quintal | Não regionalizado (nicho cogumelos) | A partir de R$ 25/mês |

**Leitura estratégica:** o modelo já está validado no Brasil — não é preciso "inventar a categoria". Mas todos os players mapeados operam em **escala pequena/regional, com tecnologia simples e preço de entrada baixo** (R$ 25–95 na maioria dos casos). Isso é duplamente informativo: (a) confirma demanda real e disposição a pagar; (b) sugere que **ninguém ainda resolveu a escala** — a oportunidade não é só "entrar no mercado", é "ser o primeiro a profissionalizar e escalar a categoria" com tecnologia própria dos dois lados (fornecedor/cliente) e operação de CD estruturada.

**Posicionamento do Clube.org:** "a cesta da estação, direto do produtor regional, sem você precisar pensar nisso toda semana."

---

### 2.4 Comparativo entre capitais candidatas (pesquisa de mercado para escolha da praça-piloto)

Cinco variáveis definem se uma capital é boa candidata para o piloto e para a ordem de expansão: **(1) densidade de fornecedores certificados a até ~100km** (viabiliza o modelo de CD regional), **(2) poder de compra**, **(3) penetração de consumo de orgânicos na região**, **(4) intensidade de concorrência já instalada**, e **(5) tamanho do mercado endereçável (população)**.

| Capital | População (2025) | Renda domiciliar per capita do estado (2025) | Penetração de orgânicos na região | Produtores certificados no estado (CNPO) | Concorrência direta já mapeada | Cinturão verde / oferta regional |
|---|---|---|---|---|---|---|
| **Curitiba (PR)** | 1,83 mi cidade / 3,72 mi região metropolitana | R$ 2.762 (5º maior do país) | Sul (sem dado regional quebrado na pesquisa) | **4.510 — o maior do Brasil**, impulsionado pelo programa estadual Paraná Mais Orgânico | Nenhum player nacional mapeado na praça | Cinturão Verde de Curitiba é polo histórico de hortaliças/agrião no Sul |
| **Porto Alegre (RS)** | Região metropolitana 4,17 mi (cidade em leve queda) | R$ 2.839 (3º maior) | Sul | **3.273 — 2º maior do Brasil** | Nenhum player nacional mapeado na praça | Citada como um dos polos de agrião/hortaliças do Sul, junto com Curitiba e BH |
| **Brasília (DF)** | 3,0 mi | **R$ 4.538 — a maior renda per capita do país** (quase o dobro da média nacional) | Centro-Oeste 42% (2ª maior penetração regional) | Não identificado no ranking nacional pela pesquisa (gap — validar no CNPO) | **Já existe concorrente direto operando (Flora Orgânicos)** | Produção agrícola do entorno do DF existe, mas cinturão verde tradicional é menos documentado que SP/PR/RS |
| **São Paulo (SP)** | **11,9 mi — maior capital do país** | R$ 2.956 (2º maior) | Sudeste 30% — **a menor penetração entre as regiões** | Não identificado no topo do ranking nacional pela pesquisa (gap — validar no CNPO) | Mercado mais concorrido: Horti Clube e outros players de hortifruti online já atuam | **Maior cinturão verde do país** (Ibiúna, Mogi das Cruzes, Biritiba Mirim — "capital estadual do agrião") |
| **Florianópolis (SC)** | Região metropolitana 1,49 mi — **maior taxa de crescimento entre as capitais grandes (+1,93%/ano)** | R$ 2.809 (4º maior) | Sul | Não identificado no ranking nacional pela pesquisa (gap — validar no CNPO) | Nenhum player nacional mapeado na praça | Cinturão verde da Grande Florianópolis documentado como fonte de abastecimento de hortifruti local |

**Leitura da tabela:**

- **Curitiba desponta como a melhor candidata a piloto**: maior densidade de fornecedores certificados do Brasil por larga margem (reduz o risco #1 do modelo — depender de poucos fornecedores), renda per capita sólida, cinturão verde já estruturado para hortaliças, e **nenhum concorrente nacional relevante identificado na praça** — janela de "primeiro a escalar" mais aberta que em SP ou Brasília.
- **Porto Alegre é a segunda melhor opção** pelo mesmo racional (2º maior estado em fornecedores certificados, sem concorrência mapeada, cinturão verde documentado).
- **Brasília tem o maior poder de compra do país e a 2ª maior penetração regional de orgânicos**, mas já tem um concorrente operando — o que valida a demanda local, mas exige diferenciação clara desde o dia 1, e falta evidência de densidade de fornecedores na pesquisa (precisa validação direta no CNPO antes de decidir).
- **São Paulo é o maior mercado endereçável em volume absoluto** e tem a melhor infraestrutura de fornecimento (maior cinturão verde do país), mas combina a **menor penetração regional de consumo** com a **maior concorrência já instalada** — atrativo para uma fase de expansão (2ª ou 3ª cidade), mas mais arriscado como piloto por exigir mais investimento em educação de mercado e diferenciação competitiva simultaneamente.
- **Florianópolis é uma aposta de nicho de alto potencial**: menor mercado em volume, mas maior crescimento populacional entre capitais grandes, renda alta e público historicamente afinado com consumo consciente — boa candidata a 3ª/4ª praça, não a piloto (mercado pequeno demais para validar unit economics com margem de erro confortável).

**Recomendação de sequência de expansão:** Curitiba (piloto) → Porto Alegre (2ª praça, mesma lógica de fornecimento no Sul, permite compartilhar aprendizado logístico) → São Paulo (3ª praça, maior mercado, mas só depois de operação madura) → Brasília e Florianópolis (4ª/5ª praças, nichos de alto ticket).

*Limitação importante: os dados de produtores certificados por estado (CNPO) são agregados estaduais, não um raio de 100km em torno de cada capital especificamente. Antes de decidir a praça-piloto, é indispensável cruzar esse dado com uma consulta direta e filtrada por município no portal do CNPO (ver metodologia na seção 4.1.1) — o comparativo acima é um funil de priorização, não a decisão final.*

### 2.5 Fontes da pesquisa de mercado

- [Qual o tamanho do mercado de orgânicos no Brasil? — Organis](https://organis.org.br/pensando_organico/qual-o-tamanho-do-mercado-de-organicos-no-brasil/)
- [Brazil Organic Food Market — IMARC Group](https://www.imarcgroup.com/brazil-organic-food-market)
- [Produção de alimentos orgânicos cresce no Brasil em 2025](https://espacoorganicoenatural.com.br/2025/05/19/producao-de-alimentos-organicos-cresce-no-brasil-em-2025/)
- [Cadastro Nacional de Produtores Orgânicos (CNPO) — MAPA](https://www.gov.br/agricultura/pt-br/assuntos/sustentabilidade/organicos/cadastro-nacional-de-produtores-organicos-cnpo)
- [Portal de Dados Abertos — CNPO](https://dados.agricultura.gov.br/dataset/cadastro-nacional-de-produtores-organicos)
- [Paraná lidera produção de orgânicos no Brasil com mais de 4,5 mil produtores certificados](https://www.band.com.br/band-parana/noticias/parana-lidera-producao-de-organicos-no-brasil-com-mais-de-45-mil-produtores-certificados-202508131533/amp)
- [IBGE: Renda per capita tem recorde em 2025](https://www.infomoney.com.br/economia/ibge-renda-per-capita-tem-recorde-em-2025-mas-ganho-dos-ricos-eleva-desigualdade/)
- [DF tem maior renda per capita do país em 2025, segundo IBGE](https://www.correiobraziliense.com.br/cidades-df/2026/02/7364515-df-tem-maior-renda-per-capita-do-pais-em-2025-segundo-ibge.html)
- [Brasil tem 15 cidades com mais de 1 milhão de habitantes — Agência Brasil](https://agenciabrasil.ebc.com.br/economia/noticia/2025-08/brasil-tem-15-cidades-com-mais-de-1-milhao-de-habitantes)
- [População na Grande Curitiba cresce em 2025 e supera 3,7 milhões](https://www.bemparana.com.br/noticias/parana/populacao-na-grande-curitiba-cresce-em-2025-e-supera-a-marca-de-37-milhoes/)
- [Cinturão Verde: o que é, importância — Grancursos](https://faculdade.grancursosonline.com.br/blog/cinturao-verde/)
- [O cinturão verde que abastece a Grande Florianópolis](https://ndmais.com.br/economia/o-cinturao-verde-que-abastece-a-grande-florianopolis/)
- [Conheça 8 clubes de assinatura gastronômicos](https://gpsbrasilia.com.br/conheca-8-clubes-de-assinatura-gastronomicos/)
- [Horti Clube — Clube de Assinaturas de Hortifruti — iFrutus](https://www.ifrutus.com.br/horti-clube)

---

## 3. Proposta de Valor e Modelo de Negócio

### 3.1 Proposta de valor

- **Para o cliente:** cesta semanal com curadoria de sazonalidade, previsibilidade de qualidade (padrão de embalagem e conferência no CD), flexibilidade (pausar, pular semana, trocar itens indesejados), preço competitivo por comprar direto do produtor sem intermediários de varejo.
- **Para o fornecedor:** canal de escoamento recorrente e previsível, visibilidade de demanda com antecedência (permite planejamento de plantio), pagamento em ciclo definido, sem necessidade de estrutura própria de venda direta ao consumidor.

### 3.2 Estrutura de planos (sugestão inicial)

| Plano | Conteúdo | Público | Ticket sugerido |
|---|---|---|---|
| Solo | 6–8 itens, ~3–4kg | 1–2 pessoas | R$ 69–89/semana |
| Família | 10–14 itens, ~6–7kg | 3–4 pessoas | R$ 119–149/semana |
| Família + | 14–18 itens, ~9kg + adicionais (ovos, temperos) | 4+ pessoas | R$ 169–199/semana |

Complementos de receita:
- **Add-ons avulsos** (ovos caipira, mel, temperos, pães artesanais de produtores parceiros) — aumenta ticket médio sem aumentar complexidade agrícola.
- **Loja avulsa (não assinante)** — canal de aquisição, permite testar o produto antes de assinar.
- **Planos corporativos** (fruteira de escritório com curadoria orgânica) — B2B como diversificação futura.

### 3.3 Cadência

Semanal como padrão, com opção quinzenal para reduzir churn de quem acha semanal "demais". Ciclo de negócio ancorado numa janela fixa (ex.: pedidos fecham domingo à noite → fornecedores entregam no CD segunda de manhã → separação/embalagem segunda → delivery terça a quinta).

---

## 4. Operação: Fornecedores → CD → Delivery

### 4.1 Fornecedores regionais

- Recrutamento de uma rede de **8–15 produtores regionais** na fase inicial, **em raio de até 100km do CD** — limite escolhido para manter o produto colhido há menos de 24–48h na cesta (a essência da proposta de "fresco e sazonal") e para manter o frete de coleta economicamente viável em rota curta.
- Cada fornecedor declara **disponibilidade semanal e preço** via app/portal próprio, com prazo de corte (ex.: sexta-feira 18h) para o CD montar o mapa de compras da semana.
- Contrato simples de fornecimento com: certificação orgânica válida (obrigatória), política de preço (fixo por safra ou reajuste por tabela), volume mínimo/máximo, prazo de pagamento (recomendado: semanal ou quinzenal, para reter fornecedores pequenos que não têm caixa para prazos longos).
- Auditoria de certificação orgânica (ver seção 7 — Compliance).
- **Diversificação obrigatória:** nenhum fornecedor deve responder por mais de ~20–25% do volume de compras semanal na fase inicial, mesmo que isso signifique pagar um pouco mais caro a um segundo/terceiro fornecedor redundante — é o seguro contra o risco #1 do modelo (quebra de safra de um único parceiro).

#### 4.1.1 Metodologia para mapear fornecedores em 100km de cada capital

O comparativo da seção 2.4 usa dados **estaduais** do CNPO (Cadastro Nacional de Produtores Orgânicos), porque a busca de mercado não permite filtrar por raio geométrico. Antes de decidir a praça-piloto, o passo obrigatório é:

1. Acessar o **CNPO** no Portal de Dados Abertos do MAPA ([dados.agricultura.gov.br/dataset/cadastro-nacional-de-produtores-organicos](https://dados.agricultura.gov.br/dataset/cadastro-nacional-de-produtores-organicos)) e baixar a planilha de produtores certificados.
2. Filtrar por **município** (não só estado) e cruzar com uma lista dos municípios a até 100km da capital candidata (ex.: para Curitiba, isso inclui a própria Região Metropolitana de Curitiba — hoje com 3,72 milhões de habitantes — além de municípios do 2º anel).
3. Geocodificar os municípios filtrados e calcular a distância real até o ponto proposto do CD (não a distância até o centro da capital — o CD pode ficar deliberadamente mais próximo do cinturão produtor que do centro urbano, desde que a logística de entrega ao cliente final ainda seja viável).
4. Classificar os produtores resultantes por cultura (para garantir cobertura de sazonalidade: folhosas, raízes, frutas, etc. — não adianta ter 20 fornecedores de alface e nenhum de raízes).
5. Fazer contato direto com uma amostra (10–20 produtores) para validar disposição real a fornecer em regime de recorrência semanal — o cadastro mostra quem *pode* fornecer, não quem *vai* fornecer nas condições do clube.

*Esse levantamento fino é trabalho de campo/analista de dados de ~1–2 semanas e deveria ser o primeiro passo prático após a leitura deste plano, antes de qualquer investimento em tecnologia ou CD.*

### 4.2 Centro de Distribuição (CD)

Fluxo operacional semanal (exemplo):

1. **Segunda de manhã:** recebimento dos produtores no CD, conferência de quantidade/qualidade (check-list de recebimento), pesagem.
2. **Segunda, meio do dia:** definição do "cardápio da semana" (o que efetivamente compôs a cesta, conforme o que chegou — é aqui que a sazonalidade acontece na prática) e atualização automática no app do cliente.
3. **Segunda à tarde/terça de manhã:** separação e montagem das cestas por plano, embalagem (caixas reutilizáveis/retornáveis ou biodegradáveis), etiquetagem por rota.
4. **Terça a quinta:** delivery por rota otimizada (frota própria para o raio urbano central + parceiro logístico terceirizado para bairros/regiões mais distantes).
5. **Sexta:** fechamento do ciclo, conciliação financeira com fornecedores, relatório de perdas/quebras, planejamento da semana seguinte.

**Infraestrutura mínima do CD (fase inicial):** câmara fria/refrigerada, bancada de separação, balanças, sistema de etiquetagem, veículo(s) refrigerado(s) próprio(s) ou parceria com transportadora especializada em perecíveis.

### 4.3 Sazonalidade como motor operacional (não só marketing)

- O catálogo **não é fixo** — é definido semana a semana pelo que os fornecedores confirmam. Isso exige que o app do cliente comunique com clareza "o que vem essa semana" (idealmente com 1–2 dias de antecedência) e permita pequenas trocas dentro do estoque disponível.
- Vantagem: menor desperdício, preço mais estável (compra-se o que está abundante), narrativa autêntica de "vegetal da estação".
- Desafio: exige tecnologia de gestão de estoque em tempo quase real e comunicação constante com o cliente para gerenciar expectativa.

### 4.4 Logística de última milha

- Fase 1 (validação): frota própria pequena (2–4 veículos) cobrindo raio urbano concentrado, rotas fixas por dia da semana.
- Fase 2 (escala): modelo híbrido — frota própria para o núcleo + parceiros terceirizados (motofrete refrigerado, transportadoras especializadas em perecíveis) para expansão de área.
- Embalagem térmica adequada para produtos que ficam algumas horas em rota sem refrigeração ativa.

---

## 5. Tecnologia

### 5.1 Site institucional + loja

- Site com: apresentação da proposta, planos e preços, "conheça os produtores" (storytelling — forte alavanca de confiança e diferenciação), blog de conteúdo (receitas, sazonalidade, conservação de alimentos) para SEO orgânico.
- Loja online para: assinatura de plano (checkout recorrente) e compra avulsa (aquisição de quem ainda não assina).

### 5.2 Aplicação de gestão — dois lados

**App/portal do fornecedor:**
- Cadastro de produtos, preço e disponibilidade semanal (com prazo de corte).
- Calendário de entregas no CD e comprovantes de recebimento.
- Emissão/anexo de nota fiscal, histórico de pagamentos e extrato financeiro.
- Indicadores simples: volume vendido, sazonalidade de demanda, previsão para planejamento de plantio.

**App/portal do cliente:**
- Escolha e gestão de plano (upgrade/downgrade, pausar semana, cancelar).
- Visualização do "cardápio da semana" com antecedência e opção de troca dentro do estoque disponível.
- Rastreamento do pedido (separado → em rota → entregue).
- Histórico, avaliação de qualidade por item (dado valioso para gestão de fornecedores) e canal de suporte.

**Backend interno (operação/CD):**
- Painel de compras consolidadas por fornecedor (o que precisa comprar essa semana, com base nas assinaturas ativas).
- Gestão de separação/embalagem (checklist por pedido) e roteirização de entrega.
- Dashboard de perdas/quebras, NPS, churn e métricas financeiras.

*Recomendação de execução:* para o MVP, evitar construir tudo do zero. Usar uma plataforma de assinatura/e-commerce (ex.: Shopify + apps de subscription, ou Vindi/Superlógica para gestão de recorrência) integrada a um app leve no-code/low-code para o portal do fornecedor, migrando para desenvolvimento proprietário quando o volume justificar (tipicamente acima de ~1.500–2.000 assinantes ativos).

### 5.3 Integração de pagamento

- Gateway com suporte a **cobrança recorrente** (assinatura) e **PIX** (alta preferência do consumidor brasileiro, inclusive para recorrência via PIX automático) — ex.: Pagar.me, Vindi, Iugu, Asaas.
- Regras de negócio: tentativa de retry automático em caso de falha de cobrança, comunicação proativa (WhatsApp/e-mail) antes de suspender a assinatura, gestão de inadimplência.
- Split de pagamento (opcional, fase 2) caso se decida repassar valor diretamente ao fornecedor automaticamente via marketplace de pagamento.

### 5.4 Redes sociais e conteúdo

- Instagram/TikTok como canais primários: conteúdo de bastidores (visita a produtores, dia de separação no CD), receitas com os itens da semana, educação sobre sazonalidade.
- WhatsApp como canal operacional (avisos de entrega, suporte) e de retenção (não só marketing).
- Parcerias com micro/nano-influenciadores locais de alimentação saudável — custo-benefício melhor que grandes influenciadores nesse estágio.
- Programa de indicação (member-gets-member) como principal canal de aquisição de baixo CAC após a validação inicial.

---

## 6. Marketing e Aquisição

| Canal | Papel | Observação |
|---|---|---|
| Indicação (member-gets-member) | Aquisição principal em regime | CAC mais baixo, maior LTV do indicado |
| Redes sociais (orgânico + pago) | Awareness e conversão topo de funil | Conteúdo de produtor/sazonalidade como diferencial |
| Parcerias locais (academias, escolas, clínicas, coworkings) | Aquisição B2B2C | Bom encaixe com público-alvo |
| SEO/conteúdo (blog de receitas) | Aquisição de longo prazo, baixo custo marginal | Investimento de médio prazo |
| Feiras/eventos locais | Aquisição + branding | Conexão direta com a experiência "produtor" |

**Retenção** é tão ou mais importante que aquisição num modelo de assinatura perecível: qualidade consistente, comunicação de sazonalidade bem feita, flexibilidade (pausar em vez de cancelar) e programa de fidelidade são as alavancas centrais.

---

## 7. Compliance e Regulatório

- **Certificação orgânica:** todo fornecedor deve ter certificação válida (por certificadora credenciada ou participação em Organismo Participativo de Avaliação da Conformidade — OPAC), conforme legislação brasileira de produtos orgânicos. Auditoria periódica da validade dos certificados é obrigatória — é o ativo de confiança central do negócio.
- **Vigilância sanitária:** o CD precisa de licença sanitária municipal/estadual adequada para manipulação e armazenamento de alimentos, com boas práticas de manipulação documentadas.
- **Nota fiscal e tributação:** estruturação tributária adequada para revenda de produtos alimentícios in natura (regras variam por estado — avaliar Simples Nacional e substituição tributária conforme UF).
- **LGPD:** dados de clientes (endereço, forma de pagamento, hábito de consumo) exigem política de privacidade e segurança de dados adequadas, especialmente nos apps.
- **CDC (Código de Defesa do Consumidor):** política clara de cancelamento, reembolso e qualidade — assinatura recorrente é escrutinada de perto por reguladores e pelo próprio consumidor quanto à facilidade de cancelamento.

---

## 8. Estrutura Organizacional (fase inicial)

| Área | Função | Fase |
|---|---|---|
| Operação/CD | Gestor de CD + equipe de separação/embalagem (2–4 pessoas) | Dia 1 |
| Logística | Motoristas/entregadores (próprios ou parceiros) | Dia 1 |
| Suprimentos | Responsável por relação com fornecedores, compras e qualidade | Dia 1 |
| Tecnologia | Squad enxuto (produto + dev, ou agência/freela no MVP) | Dia 1 (terceirizado) → interno na fase 2 |
| Marketing/CS | Growth + atendimento ao cliente (WhatsApp, redes sociais) | Dia 1 |
| Financeiro/Admin | Fundador(a) ou controller part-time | Dia 1 |

Modelo enxuto no início (fundadores acumulando funções), profissionalizando a estrutura a partir de ~500–800 assinantes ativos.

---

## 9. Análise SWOT

| Forças | Fraquezas |
|---|---|
| Relação direta com produtor (diferenciação e narrativa) | Operação intensiva em logística/perecível (baixa margem de erro) |
| Modelo recorrente (previsibilidade de receita) | Dependência de poucos fornecedores no início |
| Sazonalidade como ativo de marca | Necessidade de capital de giro para pagar fornecedor rápido |

| Oportunidades | Ameaças |
|---|---|
| Crescimento do consumo consciente/saudável | Entrada de grandes players (redes/apps de delivery) no nicho |
| Baixa penetração atual = espaço para crescer | Sazonalidade climática (quebra de safra, chuva, seca) |
| Expansão para B2B (empresas, restaurantes) | Inflação de alimentos pressionando o ticket médio |

---

## 10. Riscos e Mitigação

| Risco | Impacto | Probabilidade | Mitigação |
|---|---|---|---|
| Quebra de safra por clima (seca, chuva, praga) | Alto — falta de produto na cesta | Média-Alta | Rede diversificada de fornecedores (múltiplas culturas e regiões), catálogo flexível por semana |
| Churn alto de assinantes | Alto — mata a receita recorrente | Média | Programa de flexibilidade (pausar em vez de cancelar), qualidade consistente, comunicação proativa de sazonalidade |
| Perecibilidade/perda de produto (quebra na cadeia fria) | Médio-Alto — prejuízo direto e reclamação de qualidade | Média | Investimento em cadeia fria no CD e na entrega, checklist de recebimento e saída |
| Dependência de poucos fornecedores | Alto | Média (fase inicial) | Diversificar base de fornecedores desde o início, contratos com volume mínimo garantido |
| Capital de giro insuficiente (pagar fornecedor rápido, receber depois) | Alto | Média | Planejamento de fluxo de caixa desde o dia 1, negociar prazos de pagamento realistas com fornecedor |
| Concorrência de grandes players (iFood, redes de varejo) | Médio | Média-Alta | Diferenciação por curadoria/sazonalidade/relação com produtor — não competir só em preço/conveniência |
| Falha de certificação/compliance orgânico de um fornecedor | Alto — risco reputacional e legal | Baixa-Média | Auditoria periódica de certificados, cláusula contratual de responsabilidade |
| Complexidade/custo de tecnologia (apps duplos + pagamento) | Médio | Média | MVP com ferramentas prontas (no-code/plataformas de assinatura) antes de desenvolvimento proprietário |
| Sazonalidade gera insatisfação ("cesta pobre" em entressafra) | Médio | Média | Comunicação transparente + add-ons para complementar cesta em semanas de baixa variedade |

---

## 11. Plano Financeiro (estimativas iniciais — a validar com modelo detalhado)

> Os valores abaixo são estimativas de referência de mercado para dimensionamento inicial. Recomenda-se construir um modelo financeiro detalhado (mês a mês, 24 meses) antes de captar investimento ou comprometer capital.

### 11.1 Investimento inicial (pré-operacional)

| Item | Estimativa (R$) |
|---|---|
| Estruturação do CD (câmara fria, bancadas, balanças, embalagens) | 60.000 – 120.000 |
| Veículo(s) refrigerado(s) (compra ou entrada de leasing) | 40.000 – 90.000 |
| Site + loja online (setup em plataforma) | 15.000 – 35.000 |
| App/portal fornecedor + cliente (MVP low-code) | 40.000 – 90.000 |
| Marca, identidade visual, produção de conteúdo inicial | 15.000 – 30.000 |
| Licenças, certificações, jurídico/contratos | 10.000 – 20.000 |
| Capital de giro (2–3 ciclos de pagamento a fornecedores) | 60.000 – 120.000 |
| Reserva de contingência (~15%) | 35.000 – 75.000 |
| **Total estimado** | **≈ R$ 275.000 – 580.000** |

*Faixa ampla porque depende fortemente de: comprar vs. terceirizar frota, construir vs. usar plataforma pronta para os apps, e escala inicial (bairro-piloto vs. cidade inteira).*

### 11.2 Estrutura de custo recorrente (mensal, ilustrativo em regime — ~1.000 assinantes ativos)

| Item | % da receita (referência) |
|---|---|
| Custo de produto (pagamento a fornecedores) | 40–48% |
| Operação do CD (equipe, embalagem, energia) | 12–16% |
| Logística/última milha | 10–15% |
| Marketing e aquisição | 8–15% |
| Tecnologia (plataformas, manutenção) | 3–6% |
| Administrativo/geral | 5–8% |
| **Margem operacional alvo** | **10–18%** |

### 11.3 Unit economics (referência do setor de assinatura de alimentos frescos)

- **Ticket médio:** ~R$ 110/semana → ~R$ 440–475/mês por assinante ativo.
- **CAC alvo:** R$ 80–200 (menor via indicação, maior via mídia paga).
- **Churn mensal saudável:** abaixo de 8–10%; acima de 15% inviabiliza o modelo no médio prazo.
- **LTV:** função direta da retenção — prioridade #1 do negócio é manter churn baixo, mais do que crescer aquisição rápido demais sem CD/logística prontos para escalar.
- **Ponto de equilíbrio:** tipicamente entre 600–1.200 assinantes ativos, dependendo do tamanho do CD e da estrutura de frota (própria vs. terceirizada).

### 11.4 Recomendação de captação

Dado o perfil (operação física + tecnologia), o caminho mais comum é: **capital semente próprio/família e amigos** para validar em 1 bairro/região por 3–6 meses → captação com **investidor-anjo ou fundo pré-seed** para escalar tecnologia e expandir área de entrega, usando os dados reais de churn/CAC/LTV do piloto como prova.

---

## 12. Escalabilidade e Modelo de Expansão

O pedido central deste plano é que o negócio **seja escalável**. É importante ser honesto sobre o que isso significa aqui: este não é um negócio de software puro (marginal cost ≈ zero por novo usuário) — é um negócio **físico e operacional** (CD, cadeia fria, frota, produto perecível). Isso não o impede de escalar, mas define **qual tipo de escala é realista**.

### 12.1 O que escala "de graça" (ativos de software, replicáveis em qualquer praça nova)

- Site, loja online e apps de cliente/fornecedor — construídos uma vez, reutilizados em todas as praças.
- Marca, conteúdo, playbook de marketing e programa de indicação.
- Backend de gestão de compras/estoque/roteirização — o mesmo motor serve múltiplos CDs.
- Relacionamento com gateway de pagamento, processos de compliance/contrato-padrão com fornecedores.

### 12.2 O que **não** escala automaticamente (precisa ser recriado a cada praça nova)

- O CD físico e a cadeia fria.
- A frota/parceria de última milha local.
- A rede de fornecedores regionais (100km) — relação de confiança e contrato local, não é algo que se "copia e cola" de uma cidade para outra.
- A equipe operacional de separação/embalagem.

### 12.3 Modelo de expansão recomendado: "CD-in-a-box" replicável, não "hub único nacional"

Dado o ponto acima, o caminho de escala correto **não é** um único CD gigante tentando atender o Brasil inteiro (a logística de perecível inviabiliza distância longa), e também **não é** abrir todas as praças ao mesmo tempo. O modelo recomendado é um **playbook replicável por capital**, com portão de decisão (go/no-go) antes de abrir a praça seguinte:

1. **Provar a unidade econômica em 1 praça-piloto** (seção 2.4 recomenda Curitiba) até bater metas mínimas de churn (<10%/mês), margem de contribuição e CAC/LTV saudável, por pelo menos 2–3 ciclos trimestrais consecutivos.
2. **Documentar o playbook operacional** (como abrir um CD, como recrutar os primeiros 10 fornecedores, como configurar o app para uma nova praça) como um manual replicável, não conhecimento tácito de uma pessoa.
3. **Abrir a 2ª praça reaproveitando 80%+ da tecnologia** e testando o playbook operacional "no papel" — se a 2ª praça atingir os KPIs mais rápido que a 1ª (graças ao playbook), é sinal real de escalabilidade.
4. **Só então acelerar o ritmo de abertura** de novas praças (ex.: 1 nova capital a cada 2–3 meses), sempre com o mesmo portão de decisão.

Esse modelo é conhecido no mercado de food-tech/last-mile como **"roll-up regional"**: cada praça precisa ser lucrativa (ou no mínimo com contribuição positiva) por si só — a escala não vem de subsidiar operação deficitária com capital de investidor indefinidamente, vem de replicar uma unidade que já funciona.

### 12.4 Alavancas reais de escala dentro de cada praça já aberta

- **Aumento de densidade de entrega** (mais assinantes por rota = menor custo de última milha por pedido) — a maior alavanca de margem depois do CAC.
- **Ampliação de sortimento** (add-ons: ovos, mel, pães, temperos) para aumentar ticket médio sem aumentar complexidade agrícola.
- **B2B** (fruteira de escritório, parcerias com academias/coworkings) como segundo motor de crescimento dentro da mesma praça, aproveitando o mesmo CD.

---

## 13. Roadmap de Implementação

| Fase | Duração | Objetivo | Entregáveis-chave |
|---|---|---|---|
| **0 — Validação** | 1–2 meses | Validar demanda e operação manual | Lista de espera, 3–5 fornecedores fechados, entrega manual (planilha + WhatsApp) para ~50 clientes piloto |
| **1 — MVP tecnológico** | 2–3 meses | Sair do manual, ter recorrência de verdade | Site + checkout de assinatura, portal simples de fornecedor, pagamento recorrente/PIX, CD funcional em escala pequena |
| **2 — Escala regional** | 3–6 meses | Crescer base em uma região/cidade | App completo (cliente + fornecedor), frota otimizada, marketing de aquisição estruturado, meta de 500–1.000 assinantes |
| **3 — Expansão** | 6–12 meses | Novas regiões/cidades ou novo CD | Replicar modelo operacional, avaliar franquia/licenciamento de CD regional, expandir B2B |

---

## 14. Indicadores-Chave (KPIs)

- **Crescimento:** novos assinantes/mês, taxa de conversão do site/loja para assinatura.
- **Retenção:** churn mensal, taxa de pausa vs. cancelamento, NPS.
- **Operação:** % de perda/quebra de produto, acurácia de separação (erros por pedido), pontualidade de entrega.
- **Fornecedor:** % de disponibilidade confirmada vs. entregue, lead time de pagamento, diversidade de fornecedores ativos.
- **Financeiro:** CAC, LTV, ticket médio, margem de contribuição por assinante, fluxo de caixa semanal.

---

## 15. Veredito de Viabilidade e Escalabilidade

**Pergunta direta: o negócio é viável? É escalável?**

### Viável — sim, com ressalvas, e a evidência de mercado sustenta essa resposta.

O maior risco de qualquer plano de negócio é "essa demanda existe de verdade?". Aqui, a resposta é sim, e não é uma hipótese — **é um fato observável**: pelo menos seis operações (Flora Orgânicos, Clube Orgânico, +Q, Terra Forte, Horti Clube, Fungo de Quintal) já cobram de brasileiros por exatamente este modelo, o mercado orgânico cresce ~16% ao ano em valor, e a penetração de consumo quase dobrou desde 2017. Isso remove o maior risco binário (existe ou não existe mercado) da mesa.

Com disciplina operacional (fornecedores diversificados, cadeia fria bem gerida, churn monitorado de perto), a matemática unitária do modelo (seção 11.3) é positiva: ticket médio de ~R$ 440–475/mês por assinante, margem operacional-alvo de 10–18%, CAC administrável via indicação. **Isso é um negócio regional saudável e defensável.**

### Escalável — sim, mas não no sentido "software", e é aqui que a maioria dos negócios parecidos no mundo tropeça.

Esse é o ponto que exige honestidade, porque é onde negócios desse tipo costumam prometer mais do que entregam:

- **O que NÃO é verdade:** que este negócio escala como um app ou marketplace, com custo marginal baixo por nova cidade. Cada praça nova exige recriar CD, frota, cadeia fria e rede de fornecedores locais — ativos físicos, não digitais. Categorias parecidas no mundo (assinatura de meal-kit/hortifruti) têm histórico global de **margens finas e dificuldade real de escalar rápido mantendo qualidade** — é um padrão setorial, não uma falha de execução específica deste plano.
- **O que É verdade:** dentro desse limite físico, o modelo **é** escalável de forma disciplinada — replicando um playbook operacional provado, praça por praça (seção 12.3), com tecnologia compartilhada entre todas elas. Não escala por "ligar um switch", escala por **execução repetida e disciplinada de um manual que já funcionou uma vez**.

### Condição para a viabilidade se sustentar no médio prazo

A variável que mais decide o sucesso ou fracasso **não é aquisição de clientes — é retenção**. Um clube de assinatura de perecível vive ou morre pelo churn: se ficar consistentemente acima de ~15%/mês, o CAC nunca se paga e o negócio queima caixa indefinidamente, não importa quão bom seja o produto. Se ficar abaixo de ~10%/mês, o modelo se sustenta e a expansão praça a praça (seção 12) é genuinamente executável.

### Recomendação final

**Prosseguir — mas em modo de validação, não de expansão imediata.** Rodar a Fase 0 (seção 13, validação manual com ~50 clientes em 1 praça) antes de qualquer investimento pesado em tecnologia ou CD permanente. Se o piloto sustentar churn saudável e margem de contribuição positiva por 2–3 trimestres, o caso de negócio (e o caso de escala) está provado com dados próprios — não apenas com a evidência indireta deste documento — e a expansão praça a praça deixa de ser uma aposta para virar execução de um modelo validado.

---

## 16. Próximos Passos Recomendados

1. Rodar a **Fase 0 (validação manual)** com 3–5 fornecedores e ~50 clientes piloto antes de investir pesado em tecnologia — reduz risco e gera dados reais para o modelo financeiro.
2. Construir um **modelo financeiro detalhado mês a mês** (24 meses) a partir dos números reais do piloto, refinando as estimativas deste documento.
3. Validar **Curitiba como praça-piloto** (indicação da seção 2.4) com o levantamento fino de fornecedores em 100km descrito na seção 4.1.1, e definir o bairro/região de instalação do CD com base na proximidade real do cinturão verde.
4. Desenhar o **MVP tecnológico enxuto** (plataforma pronta + integrações), evitando desenvolvimento proprietário caro antes de validar retenção.
5. Formalizar **contratos-padrão com fornecedores** (preço, volume, prazo de pagamento, auditoria de certificação).

---

*Documento gerado como ponto de partida estratégico. Recomenda-se validação de premissas de mercado e financeiras com dados primários (pesquisa com público-alvo, cotação real de fornecedores e logística) antes de decisões de investimento.*

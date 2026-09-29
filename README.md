# ATKFUT — Landing page (versão Catálogo)

Visual claro e editorial, com **exemplo de cálculo passo a passo** (fórmula + tabela com números hipotéticos) em vez de simulador.

- Ao vivo: https://paulo-henr1que.github.io/atkfut-landing-catalogo/
- Outra variação (escura/app): https://github.com/Paulo-Henr1que/atkfut-landing-ledger

Site estático (`index.html` + `style.css`), sem build.

## Base de conteúdo

Tudo que a página afirma sobre o app vem do site original ([atkfornecedor.com](https://atkfornecedor.com/)): pedido mínimo de 5 peças, escolha de times e modelos, catálogo, preço de fornecedor, ofertas e notificações no app, pagamento pelo app, links oficiais da App Store e do Google Play e as 4 avaliações de clientes publicadas lá. Nenhum recurso, número ou depoimento foi inventado.

## Decisões de conformidade (Google Ads / TikTok Ads)

| Original | Nesta versão | Por quê |
|---|---|---|
| "Fornecedor Oficial" | "Catálogo atacadista" | "Oficial" junto a marcas de terceiros agrava a política de bens falsificados / PI |
| "Lucre R$80 a R$130 por camisa", "+R$12.000/mês" | Fórmula da conta + exemplo marcado como hipotético, incluindo custos de frete e taxas | Alegação de renda não substanciada (Misrepresentation / Business Opportunity) |
| "Multiplique o lucro", "mercado sempre quente" | "Repita quando fizer sentido" | Promessa implícita de resultado |
| — | Seção "Antes de começar" com quem **não** deve entrar | Revisores de oportunidade de negócio valorizam expectativas realistas |
| — | Ilustrações de camisa genéricas, sem escudo nem marca, identificadas como ilustração | Evitar uso de marca de terceiros na página |

## Risco que continua fora do alcance da página

**Bens falsificados / propriedade intelectual.** Se o catálogo vende réplicas com escudos de clubes e logos de fabricantes sem licença, Google Ads e TikTok Ads podem reprovar ou suspender a conta independentemente do texto da landing page. Não use fotos de produto com marcas de terceiros nos criativos de anúncio. A solução definitiva é produto licenciado.

## Pendências

1. Inserir o CNPJ no rodapé (há um `<!-- TODO -->` no `index.html`).
2. Se for anunciar como oportunidade de negócio no TikTok Ads, verificar se a categoria exige aprovação prévia.
3. Se adicionar formulário ou pixel de rastreamento, incluir página de política de privacidade.

# Plano: Página de Vendas - Pack Aula Mágica

## Especialista(s) Ativo(s)
- @[frontend-specialist] (Arquitetura UI/UX, Design Systems, Mobile-First)
- Especialista em CRO e Copywriter

## 🎨 Design Commitment (Anti-Safe Harbor)
- **Topologia:** Vertical Narrative focada em visualização contínua (Mobile-first). Ao invés de blocos genéricos, teremos transições suaves integrando as seções.
- **Geometria:** Formas lúdicas, "soft but bold". Estilo "Bobby Goods" com bordas em 24px-32px (amigáveis) e sobreposição de cartões para causar profundidade e movimento.
- **Paleta (Sem Roxo!):** 
  - Fundo/Corpo: Tons Pastéis Suaves (Bege Areia `#F9F6F0`, Amarelo Manteiga `#FFF9D2`).
  - Destaques (Contraste): Verde Vibrante (`#22C55E`) ou Laranja Vivo (`#F97316`) para CTAs e Preços.
- **Tipografia:** `Poppins` (Pesos bold/extrabold para headlines e semibold para CTAs). Grande peso tipográfico.
- **Micro-interações:** Hover com escala suave, cronômetro pulsante (efeitos de urgência) e cards de depoimentos com entrada em *stagger*.

## Estrutura da Página (Mobile-First)
1. **Headline & Subheadline:** Promessa Forte. Palavras-chave destacadas.
2. **VSL:** Container central com shadow profunda e bordas arredondadas (Lúdico + Profundidade).
3. **Galeria "Dê uma espiadinha":** Grid com scroll horizontal (Mobile friendly) para mostrar conteúdos.
4. **Bônus Exclusivos:** Seção com ênfase visual (ícones/mockups).
5. **Ancoragem (Planos):** Tabela de preços lado a lado (destaque Premium em Z-index).
6. **Feedbacks:** Balões estilo chat.
7. **Cards de Benefícios:** Rápidos e diretos.
8. **FAQ:** Acordeão dinâmico minimalista.
9. **Escassez:** Cronômetro pegando toda a largura na parte inferior ou fixo (*sticky*) com cor gritante.
10. **CTA Final:** Botão que pulsa (Spring Physics).

## Passos para Implementação (Pendente Aprovação)
1. Construir `index.html` e estilização (via Tailwind ou CSS puro customizado).
2. Adicionar JavaScript para o Timer de 10 minutos, FAQ e entrada suave.
3. Revisão técnica (CRO + Layout).

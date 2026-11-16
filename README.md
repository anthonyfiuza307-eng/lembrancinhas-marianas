# Landing Page: Acervo de Lembrancinhas Católicas (Versão Otimizada)

Landing page de alta conversão para venda do acervo de moldes em PDF de lembrancinhas católicas (Todas as Nossas Senhoras + Coleção Especial Menino Jesus).

---

## 🎨 Paleta de Cores e Identidade Visual (Arte Sacra & Papelaria Fina)

- **Fundo das seções claras:** Off-white / creme suave (`#FAF8F5`)
- **Fundo dos cards:** Branco puro (`#FFFFFF`)
- **Cor primária de autoridade:** Azul Mariano profundo (`#162A45`)
- **Detalhes e bordas litúrgicas:** Dourado litúrgico fosco (`#C59B27`)
- **Botões de CTA:** Dourado vibrante de alto contraste (`#D4A017` / `#C59210`) com tipografia escura (`#162A45`), padding generoso (`18px 36px`), tamanho 18px e presença encorpada.

---

## ⚡ Atualizações Recentes

1. **Mockup Transparente Integrado na Hero Section:**
   - O mockup oficial está em formato PNG transparente ([`mockup-acervo.png`](file:///c:/Users/antho/OneDrive/Documentos/molde%20religioso/mockup-acervo.png)) sem caixa, sem borda e sem fundo preto, fundindo-se de forma 100% natural sobre a textura azul da Hero.
2. **Único Timer Fixo no Topo:**
   - Barra fixa no topo (`position: fixed; top: 0; width: 100%`) com `⏱️ Último dia para garantir` e o contador regressivo em tempo real até 23:59:59 (fuso de Brasília). O timer duplicado interno foi removido e o espaçamento superior ajustado.
3. **Botões de Ação (CTAs) Encorpados:**
   - Altura confortável (`min-height: 58px`), padding expandido (`18px 36px`), fonte de `1.1rem` (18px) com peso extra-bold (`800`) e sombras suaves para garantir alta presença e taxa de cliques no Desktop e Mobile.
4. **Popup de Upsell no Plano Básico (R$ 19,99):**
   - Ao clicar no botão do **Plano Básico**, a página abre um modal responsivo e elegante oferecendo o upgrade para o **Plano Completo Vitalício + 3 Bônus por apenas R$ 19,99**.
   - Possui botão principal destacado para o checkout promocional e link discreto para quem optar por manter apenas o plano básico.

---

## ⚙️ Onde Inserir seus Links de Checkout

No arquivo [`index.html`](file:///c:/Users/antho/OneDrive/Documentos/molde%20religioso/index.html):
- **Plano Básico (R$ 12,90):** localize `href="#checkout-basico"` e insira a URL de pagamento do plano básico.
- **Plano Completo Regular (R$ 24,90):** localize `href="#checkout-completo"` e insira a URL do plano completo.
- **Plano Completo com Desconto de Upsell (R$ 19,99):** localize `href="#checkout-upsell"` e insira a URL da oferta promocional de R$ 19,99 do popup.

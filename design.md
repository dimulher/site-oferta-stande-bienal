# design.md — Estande Bienal NAB (Oferta Autógrafos/Podcast/Palestra)

> LP de reserva de espaço no estande da NAB na Bienal do Livro. Copiado do layout de `site-oferta-nab` (Oferta de Entrada NAB).

## 1. Identidade & Tom
- **Projeto:** Landing da oferta de estande na Bienal (NAB)
- **Setor:** Editora — experiência presencial de autores
- **Sensação visual:** editorial premium, claro, sofisticado (mesmo padrão NAB)

## 2. Cores
| Papel | Hex | Uso |
|-------|-----|-----|
| Marfim (base) | `#FAF6EE` | fundo principal |
| Marfim 2 | `#FBF5E9` / `#F2EAD9` | seções alternadas |
| Branco | `#FFFFFF` | cards |
| Dourado | `#E6D29A` / `#E3C56B` | destaques premium |
| Bordô | `#B44B3B` | CTA / ênfase |
| Navy | `#0E1A32` | blocos escuros (combo, ticker) |

## 3. Tipografia
- **Títulos:** Playfair Display — 400/600/700/800/900 (+ itálico 500)
- **Corpo:** Montserrat — 300/400/500/600/700

## 4. Estrutura da página
1. Header fixo (logo + CTA)
2. Hero + proof bar (700 mil pessoas / 500+ autores)
3. Manifesto (dor: publicar ≠ ser visto)
4. Galeria do estande (renders 3D reais extraídos do PDF `NOVO STAND 2026.pdf`)
5. VSL (placeholder — trocar por vídeo do expert quando pronto)
6. Planos (3 cards + combo em destaque)
7. Autoridade da editora + ticker de estatísticas
8. Galeria marquee da Bienal (fotos reais de edições anteriores)
9. Pra quem é
10. Oferta + form (seletor de plano + botão pro Spotform)
11. FAQ
12. Footer

## 5. Oferta — planos e preços
| Plano | Inclui | Preço |
|---|---|---|
| Sessão de Autógrafos | Mesa de autógrafos, 1h | 12x R$150 |
| Espaço para Podcast | Espaço reservado, 1h (obs: sem áudio/vídeo) | 12x R$60 |
| Palco de Palestra | 1h + microfone + TV 86" + operador (obs: sem foto/vídeo) | 12x R$100 |
| Combo Completo | Os 3 formatos | 12x R$270 ou R$3.000 à vista |

## 6. Pendências (rastrear aqui)
- [ ] Definir nome/marca da oferta
- [ ] Criar formulário no Spotform e colar link em `CHECKOUT_URL` (index.html, fim do arquivo)
- [ ] Adicionar fotos reais do estande em uso (substituir/complementar renders 3D)
- [ ] Produzir VSL do expert e substituir o bloco `.vsl-frame` por vídeo real
- [ ] Produzir vídeo do estande e definir onde entra (sugestão: logo após a galeria de renders)
- [ ] Configurar Pixel de conversão específico se for conta diferente da atual (599258489828023)
- [ ] Hospedar (Vercel) quando aprovado

## 7. Motion
- Sutil, fade-up on scroll
- **Reduced-motion:** IGNORAR — Dede quer animações tocando

## 8. Regras
- ✅ Tema claro marfim + dourado + bordô (padrão NAB aprovado)
- ❌ Não usar dark theme na base (só blocos de destaque como o combo)

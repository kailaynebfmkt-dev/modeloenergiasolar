# Hélio Verde Energia Solar: dados a confirmar antes de publicar

O site é o `index.html` (CSS e JS embutidos) + pasta `img/` com as 4 fotos.

## Contatos (trocar pelos dados reais)
Procure e substitua no `index.html`:

| O que | Está assim | Onde |
|---|---|---|
| WhatsApp (só números, com 55) | `5551999990000` | `CONFIG.whats` no script e nos `href="https://wa.me/..."` |
| WhatsApp exibido | `(51) 99999-0000` | rodapé |
| Telefone | `(51) 3000-0000` / `tel:+555130000000` | rodapé |
| E-mail | `contato@helioverde.com.br` | rodapé |
| Endereço e horário | Av. Emancipação, 1250, Centro, Tramandaí/RS | rodapé |
| Redes sociais | links para a página inicial de cada rede | rodapé (`.soc`) |

## Conteúdo
- Os 3 depoimentos (nome, cidade, texto) devem ser trocados por clientes reais e autorizados.
- Números dos contadores (2.800 sistemas, 95%, 25 anos, 12.000 t) seguem o briefing; confirme que são os oficiais.
- Simulador: conta estimada = 5% da conta atual, mínimo R$ 45 (função `sim()` no script).
- Meta tags (title, description, og) no `<head>`; falta uma imagem `og:image` para compartilhamento.

## Fotos (`img/`)
- `tecnico-por-do-sol.jpg` tem só 236x354 px; está pequena de propósito (arco dos depoimentos). Troque por uma versão HD se tiver.
- `residencial.jpg`, `instalacao.jpg`, `rural.jpg`: usadas nos 3 cards de Soluções.

## Fontes
Syne e Manrope vêm do Google Fonts (precisa de internet). Sem elas o site usa fontes do sistema.

# Disco Coffee Club — Site pronto (Vercel)

## Como publicar
1. Faça upload desta pasta para um repositório (GitHub).
2. Importe no **Vercel**.
3. Em *Settings → Environment Variables*, adicione `MP_ACCESS_TOKEN` com o Access Token do Mercado Pago.
4. Deploy. O botão **Finalizar compra** cria a preferência e abre o **Checkout Pro** (PIX, cartão e parcelamento).

## Frete
- O endpoint `/api/frete` calcula **frete estimado** por CEP (consulta a UF via ViaCEP e usa uma tabela de zonas PAC/SEDEX).
- Se quiser frete oficial dos Correios, troque a lógica desse endpoint por uma integração de sua preferência.

## Imagens
As imagens já estão no diretório raiz (logo e fotos).


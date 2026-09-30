# Ofício Barbearia

Site one-page para uma barbearia, feito como projeto de portfólio. A marca, o endereço e a equipe são fictícios.

**Ver o site:** https://matheusfargomes-beep.github.io/oficio-barbearia/

## O que o site faz

- **Comanda interativa:** o cliente marca os serviços e o site calcula o total e o tempo na cadeira, com desconto automático no combo cabelo + barba. O botão abre o WhatsApp com a mensagem de agendamento já escrita.
- **Status "aberto agora":** confere o horário de São Paulo e mostra se a barbearia está aberta, quando fecha ou quando abre de novo. Destaca o dia de hoje na tabela de horários.
- **Tabela de preços em abas:** Cabelo, Barba e Química, com tempo médio de cada serviço.
- **Cortes em alta:** low fade, mid fade, high fade, taper, buzz cut e crop francês, com ilustração em SVG gerada por código e o número do pente de cada corte.
- **Clube de assinatura:** três planos mensais, cada um com botão que abre o WhatsApp.
- **Animações:** poste de barbeiro girando, entrada do título, faixa de serviços em movimento, anéis girando e entrada dos blocos conforme a rolagem.
- **Responsivo:** funciona no celular, com menu próprio. Respeita a opção de reduzir movimento do sistema.

## Tecnologias

HTML, CSS e JavaScript puro, sem framework e sem dependências. O único recurso externo são as fontes do Google Fonts (Big Shoulders Display, Hanken Grotesk e Instrument Serif).

## Como rodar

Abra o `index.html` no navegador. Não precisa instalar nada.

## Para usar com um cliente real

Troque o texto, os preços e o horário no começo do `<script>` (constantes `CATS` e `HOURS`) e coloque o número da barbearia nos links do WhatsApp (`https://wa.me/55DDDNUMERO?text=...`).

---

Feito por **Matheus Gomes**, com apoio de IA (Claude).
[LinkedIn](https://www.linkedin.com/in/matheus-gomes-916330354/) · [GitHub](https://github.com/matheusfargomes-beep)

Quer um site assim para o seu negócio? Me chama no LinkedIn.

# Meus Gastos

App offline para controlar gastos: cartão, contas avulsas, assinaturas e categorias próprias.
Os dados ficam salvos no próprio aparelho.

## Como gerar o APK
1. Envie todos os arquivos deste projeto para um repositório no GitHub (branch `main`).
2. Abra a aba **Actions**. O build roda sozinho a cada push, ou clique em **Run workflow**.
3. Quando terminar (uns 5 a 10 minutos), abra a execução e baixe **meus-gastos-apk** em *Artifacts*.
4. Extraia o zip e instale o `app-debug.apk` no celular (permita instalar de fontes desconhecidas).

## Como editar o app
Todo o app está em `www/index.html`. Mudou algo, faça commit e o APK é gerado de novo.
O ícone fica em `resources/icon.png` (1024x1024).

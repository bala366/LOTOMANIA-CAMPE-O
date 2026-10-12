# Lotomania Espelho V10 — Android

Projeto Android Java nativo. Abre TXT/CSV pelo seletor do Android (entre em Downloads), confere concursos, analisa as 137 combinações de 2 pares de tirinhas vizinhas, pede aprovação das 20 dezenas, completa 30 consultivas (15 Primo + Fibonacci, 10 Puro Par, 5 Puro Ímpar, com complemento) e gera PDF + CSV em **Download/Lotomania combinações de tiras** usando MediaStore.

## Gerar APK pelo GitHub
1. Crie um repositório vazio no GitHub.
2. Envie **o conteúdo desta pasta**, incluindo `.github/workflows/android-apk.yml` (não envie o ZIP como um arquivo único).
3. Entre em **Actions → Gerar APK Lotomania Espelho V10 → Run workflow**.
4. Após o job concluir, baixe o artefato `LOTOMANIA_ESPELHO_V10_APK`, extraia `app-debug.apk` e instale no Android.

## Limitações
- O seletor de documentos do Android é diferente da lista numerada do terminal Pydroid. Escolha o TXT/CSV em Downloads.
- TXT aceito: 20 dezenas por linha ou número do concurso + 20 dezenas; CSV com cabeçalhos Bola1..Bola20. Arquivos com colunas extras sem cabeçalhos reconhecíveis exigem adaptação.
- Os rankings são estatísticas históricas, sem previsão garantida de sorteios futuros.
- É um APK **debug** para testes, não uma versão assinada para a Play Store.

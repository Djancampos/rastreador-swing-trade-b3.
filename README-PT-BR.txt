RASTREADOR SWING TRADE B3 — PROJETO ANDROID

Este pacote contém o projeto Android que abre seu HTML em um aplicativo Android (WebView).
O HTML original foi mantido dentro de app/src/main/assets/index.html.

IMPORTANTE
- Este ZIP é o PROJETO-FONTE, não é o APK já compilado.
- O app precisa de internet para carregar Tailwind, a biblioteca de gráficos e a integração de cotações/API que o HTML usa.
- Os dados locais dependem do armazenamento WebView do Android.
- Cotações simuladas ou antigas no HTML não devem ser tratadas como preços atuais.
- Este APK de depuração não é uma versão assinada para publicação na Play Store.

COMO GERAR O APK SEM INSTALAR ANDROID STUDIO (GitHub Actions)
1. Entre em https://github.com e crie um repositório novo (pode ser privado).
2. Descompacte este ZIP no computador e envie TODOS os arquivos/pastas para o repositório.
3. Abra a aba "Actions".
4. Se o GitHub pedir, habilite Actions para o repositório.
5. Execute "Build Android APK" em "Run workflow" (ou aguarde o build ao enviar para a branch main).
6. Quando o processo terminar com sucesso, abra a execução e baixe o artefato "Rastreador-Swing-Trade-B3-APK".
7. Descompacte o artefato; o arquivo será app-debug.apk.
8. Envie o APK ao celular e abra-o. Talvez seja necessário autorizar "Instalar apps desconhecidos" para o aplicativo usado para abrir o arquivo.

ALTERNATIVA: ANDROID STUDIO
Abra esta pasta como projeto existente no Android Studio, aguarde a sincronização do Gradle e execute Build > Build APK(s).
O APK de depuração normalmente será criado em app/build/outputs/apk/debug/app-debug.apk.

SEGURANÇA
Instale APKs apenas de fontes em que confia. Não compartilhe seu token da API Brapi. Este projeto ainda precisa ser testado no seu aparelho antes de uso real.

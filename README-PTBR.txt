FUTEBOL DE RUA MOBILE — GERAR APK PELO CELULAR

Este projeto usa GitHub Actions para compilar o APK na nuvem. Você não precisa instalar Android Studio no celular.

PASSOS:
1. No navegador do celular, entre em https://github.com e crie uma conta ou faça login.
2. Crie um repositório novo (New repository), com nome FutebolDeRuaMobile. Pode deixar Public para facilitar e não marque para criar README.
3. Abra o repositório e use Add file > Upload files. Envie os arquivos e pastas deste ZIP extraídos. É importante que .github/workflows/build-apk.yml também seja enviado.
4. Toque em Commit changes.
5. No repositório, abra a aba Actions. Se aparecer um aviso para habilitar workflows, habilite.
6. Abra o workflow "Build Android APK". Se não começar sozinho, toque em Run workflow.
7. Aguarde terminar com um sinal verde. Abra a execução concluída e procure Artifacts.
8. Baixe "FutebolDeRuaMobile-APK.zip" e extraia no celular. Dentro estará app-debug.apk.
9. Toque no APK para instalar. Se o Android bloquear, permita instalar apps desconhecidos para o navegador/gerenciador de arquivos que você usou e tente novamente.

OBSERVAÇÕES:
- O APK é uma versão de teste (debug), não publicada na Play Store.
- Não compartilhe sua senha do GitHub com ninguém.
- O projeto usa Android Gradle Plugin 8.7.3, Java 17 e Android SDK 35.

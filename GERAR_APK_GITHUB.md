# Gerar MarineBurger-Administracao.apk sem AndroidIDE

Este projeto já contém um workflow do GitHub Actions em `.github/workflows/build-apk.yml`.

## Pelo celular

1. Crie uma conta/acesse o GitHub.
2. Crie um repositório novo, por exemplo `marine-burger-administracao`.
3. Envie **todo o conteúdo desta pasta** para a raiz do repositório. Não envie a pasta externa como uma segunda camada.
4. Abra a aba **Actions** do repositório.
5. Se o GitHub pedir, permita workflows.
6. Abra **Gerar APK Marine Burger Administração**.
7. Toque em **Run workflow** e confirme.
8. Aguarde o término com status verde.
9. Abra a execução concluída e, em **Artifacts**, baixe `MarineBurger-Administracao-APK`.
10. Dentro do ZIP estará `MarineBurger-Administracao.apk`.

O workflow instala Java 17, Android SDK 34 e Gradle 8.2.1 e executa `assembleDebug`.

## Observação

O APK é uma versão debug para instalação/teste. Para distribuir publicamente pela Play Store, é necessário configurar assinatura de release.

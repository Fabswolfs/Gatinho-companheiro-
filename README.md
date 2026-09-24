# 🐱 Gatinho Companheiro — Android v1.0

Primeiro protótipo funcional do app: gatinho virtual, frases, humor, lembretes/notificações, diário simples, tela de ajuda e widget Android.

## Tecnologia
- Kotlin
- Jetpack Compose / Material 3
- Android App Widgets com Jetpack Glance
- SharedPreferences para dados locais do MVP
- AlarmManager + notificações para lembretes

## Como gerar o APK sem PC
Este projeto já inclui `.github/workflows/android.yml`.
1. Crie um repositório no GitHub pelo celular.
2. Envie todos os arquivos deste projeto para a branch `main`.
3. Abra **Actions → Build Android APK → Run workflow**.
4. Ao terminar, abra a execução e baixe o artefato `gatinho-companheiro-debug-apk`.
5. Extraia o APK no celular e instale (pode ser necessário permitir instalação do arquivo pelo navegador/gerenciador de arquivos).

## Observações
- Este é um MVP técnico. O sistema de mensagens entre usuários ainda fica para a versão 1.1.
- O visual é uma ilustração original aconchegante, inspirada em animação artesanal, sem copiar personagens de obras existentes.
- O diário atual é uma base visual; persistência completa pode ser adicionada na próxima iteração.
- Lembretes usam data no formato `dd/MM/yyyy` e horário `HH:mm`.
- Em Android recente, notificações e alarmes exatos podem exigir permissões do sistema.

## Próximos passos
1. Melhorar o personagem e trocar o rosto em texto por arte/frames reais.
2. Adicionar animações do gatinho ao widget.
3. Persistir o diário com Room.
4. Criar contas e mensagens com backend seguro.
5. Preparar ícone, splash screen, política de privacidade e versão de produção.

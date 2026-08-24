# Nexus Drive

Cofre e leitor de projetos do Alight Motion, direto no Android.

## Site

Landing oficial: https://nexusdrivehub.github.io/nexus-drive/

## Baixar o app

APK atual e histórico nas [GitHub Releases](https://github.com/nexusdrivehub/nexus-drive/releases).

## Publicar uma atualização

1. Crie a release com a tag da versão (ex.: v2.14.2) e anexe o APK
2. Edite o `versao.json` direto no site (ícone de lápis): nova versão e nova URL do APK

Pronto. A landing carrega o `versao.json` sozinha: os números de versão e os botões de download se atualizam automaticamente. O `index.html` só muda quando houver alteração de design ou texto.

O app consulta o `versao.json` desta raiz para oferecer a atualização.

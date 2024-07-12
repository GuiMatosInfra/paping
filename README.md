<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instalação do paping no Debian</title>
</head>
<body>
    <h2>Instalação do paping no Debian</h2>
    <ol>
        <li><strong>Abra o Terminal:</strong> Pressione <code>Ctrl + Alt + T</code> ou procure por "Terminal" no menu de aplicativos.</li>
        <li><strong>Adicione o Repositório <code>universe</code>:</strong>
            <pre><code>sudo nano /etc/apt/sources.list</code></pre>
            <p>Adicione a linha ao final do arquivo:</p>
            <pre><code>deb http://archive.ubuntu.com/ubuntu bionic universe</code></pre>
            <p>Salve o arquivo e feche o editor.</p>
        </li>
        <li><strong>Atualize o Índice de Pacotes:</strong>
            <pre><code>sudo apt update</code></pre>
        </li>
        <li><strong>Instale o paping:</strong>
            <pre><code>sudo apt install paping</code></pre>
        </li>
        <li><strong>Verifique a Instalação:</strong>
            <pre><code>paping --help</code></pre>
            <p>Isso deve exibir a ajuda e as opções disponíveis do <code>paping</code>, confirmando que está pronto para uso.</p>
        </li>
    </ol>
</body>
</html>

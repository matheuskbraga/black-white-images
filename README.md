# 🖼️Conversor de Imagens para Preto e Branco

Este é um script simples em Python que automatiza a conversão de imagens coloridas para preto e branco (escala de cinza). Utilizando a biblioteca Pillow, ele lê todas as imagens .jpg de uma pasta de origem, converte-as e salva o resultado numa nova pasta.
✨ Como Funciona

O script realiza as seguintes ações:

    Verifica se a pasta de destino (fotos_preto_branco) já existe. Se não existir, ela é criada.

    Lê todos os nomes de ficheiros que contêm .jpg dentro da pasta de origem (fotos).

    Para cada ficheiro, abre a imagem, aplica a conversão para o modo de luminância ('L'), que a transforma em escala de cinza.

    Salva a nova imagem em preto e branco na pasta de destino, mantendo o nome original.

🚀 Como Usar:

Para executar este projeto na sua máquina local, siga os passos abaixo.
Pré-requisitos

    Python 3.x instalado na sua máquina.

1. Clone o Repositório

Primeiro, clone este repositório para o seu computador:

    git clone https://github.com/matheuskbraga/black-white-images.git

Depois, entre na pasta do projeto:

    cd NOME-DA-PASTA-DO-PROJETO

2. Instale as Dependências

Este projeto depende da biblioteca Pillow. Para instalá-la, execute o seguinte comando no seu terminal:

    pip install Pillow

3. Prepare as Pastas e Ficheiros

    Na pasta principal do projeto, crie uma subpasta chamada fotos.

    Coloque todas as imagens no formato .jpg que você deseja converter dentro desta pasta fotos.

4. Execute o Script

Com tudo preparado, basta executar o script Python:

    python grayscale.py

Após a execução, uma nova pasta chamada fotos_preto_branco será criada (se ainda não existir) e conterá todas as suas imagens convertidas.
🎯 Resultado Esperado

O script transformará as suas imagens coloridas em versões em escala de cinza, de forma rápida e automática.
🤝 Contribuições

Sinta-se à vontade para fazer um "fork" deste projeto e sugerir melhorias. Todas as contribuições são bem-vindas!

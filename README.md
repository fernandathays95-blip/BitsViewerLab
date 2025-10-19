# Bits Viewer Lab - Ultra Hardcore

Visualizador de bits completo que permite:

- Arrastar e soltar arquivos ou selecionar da galeria.
- Mostrar todos os bits do arquivo em **binário**.
- Abrir a **câmera** do dispositivo e tirar foto.
- Copiar os bits diretamente ou baixar como `.txt`.

---

## Acessar o HTML / Demonstração

[![Abrir HTML](https://img.shields.io/badge/Abrir-HTML-brightgreen?style=for-the-badge)](BitsViewerLab.html)
[![Baixar Exemplo](https://img.shields.io/badge/Baixar-exemplo.txt-blue?style=for-the-badge)](exemplo.txt)
[![Ver no GitHub](https://img.shields.io/badge/Repositorio-GitHub-lightgrey?style=for-the-badge)](https://github.com/seu-usuario/BitsViewerLab)

> Clique nos botões acima para abrir o HTML interativo, baixar o exemplo de bits ou visitar o repositório.

---

## Estrutura do Projeto
/BitsViewerLab/
├─ README.md
├─ BitsViewerLab.html
├─ exemplo.txt

- **BitsViewerLab.html** → HTML completo que roda no navegador e implementa todas as funcionalidades.  
- **exemplo.txt** → Arquivo de teste com bits simulados.  

---

## Como usar

1. Abra o arquivo `BitsViewerLab.html` no navegador.
2. Você poderá:
   - Arrastar ou selecionar arquivos.
   - Abrir a câmera e tirar fotos.
   - Visualizar os bits em binário.
   - Copiar os bits ou baixar como `.txt`.

---

## Exemplo de arquivo de teste

Crie `exemplo.txt` com conteúdo:
Olá, Bits Viewer Lab!
Ao abrir no HTML e carregar, os bits exibidos serão:01001111 01101100 01100001 00101100 00100000 01000010 01101001 01110100 01110011 00100000 01010110 01101001 01100101 01110111 01100101 01110010 00100001

- Cada byte é mostrado em **8 bits**.  
- Linhas de 16 bytes para melhor leitura.

---

## Funcionalidades detalhadas

| Botão / Função        | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| Arrastar arquivo       | Solte qualquer arquivo para ler os bits.                                  |
| Selecionar arquivo     | Abra seletor de arquivos para escolher um arquivo.                        |
| Carregar Bits          | Lê o arquivo selecionado e exibe os bits.                                  |
| Baixar .txt            | Salva os bits em um arquivo de texto.                                      |
| Abrir Câmera           | Ativa a câmera do dispositivo (navegadores modernos).                     |
| Tirar Foto             | Captura a imagem da câmera e converte em bits no viewer.                  |

---

## Créditos

- Desenvolvido como **Bits Viewer Lab Ultra Hardcore** por fernanda.  
- Simula visualização de bits, carregamento de arquivos e captura de fotos.

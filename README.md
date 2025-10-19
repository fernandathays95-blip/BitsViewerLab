# Bits Viewer Lab - Ultra Hardcore

Visualizador de bits completo que permite:

- Arrastar e soltar arquivos ou selecionar da galeria.
- Mostrar todos os bits do arquivo em **binário**.
- Abrir a **câmera** do dispositivo e tirar foto.
- Copiar os bits diretamente ou baixar como `.txt`.
- Visualizar miniaturas das imagens carregadas com seus bits.

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
---

## Exemplo de Miniatura + Bits

Você pode incluir imagens pequenas de teste (`exemplo.png`) para pré-visualizar bits:

<table>
<tr>
<td>
<img src="exemplo.png" alt="Exemplo" width="150">
</td>
<td>
01001111 01101100 01100001 00101100 00100000 01000010
01101001 01110100 01110011 00100000 01010110 01101001
01100101 01110111 01100101 01110010 00100001
</td>
</tr>
</table>

> Cada byte é mostrado em **8 bits**, linha única para fácil cópia.

---

## Funcionalidades Detalhadas

| Botão / Função        | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| Arrastar arquivo       | Solte qualquer arquivo para ler os bits.                                  |
| Selecionar arquivo     | Abra seletor de arquivos para escolher um arquivo.                        |
| Copiar Bits            | Copia todos os bits exibidos para o clipboard.                            |
| Baixar .txt            | Salva os bits em um arquivo de texto.                                      |
| Abrir Câmera           | Ativa a câmera do dispositivo (navegadores modernos).                     |
| Tirar Foto             | Captura a imagem da câmera e converte em bits no viewer.                  |
| Miniatura              | Mostra a imagem carregada diretamente no README.                           |

---

## HTML Interativo no README

Você também pode usar HTML embutido para mostrar previews diretamente:


<img src="exemplo.png" width="150" alt="Preview">
<pre>
01001111 01101100 01100001 00101100 00100000 01000010
01101001 01110100 01110011 00100000 01010110 01101001
01100101 01110111 01100101 01110010 00100001
</pre>

## Como Usar
	1.	Abra BitsViewerLab.html no navegador.
	2.	Arraste ou selecione arquivos, abra a câmera ou tire fotos.
	3.	Veja os bits em tempo real.
	4.	Copie ou baixe os bits como .txt.
	5.	Miniaturas de imagens e bits podem ser adicionadas no README com <img> + <pre>.

## Créditos
	•	Desenvolvido como Bits Viewer Lab Ultra Hardcore por fernanda.
	•	Suporta upload, câmera, cópia, download e miniaturas.

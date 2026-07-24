# 🖇️ File Renamer

Aplicação desktop em **Python** com **PyQt6** para renomear arquivos em lote, removendo um trecho de texto dos nomes de todos os arquivos de uma pasta selecionada.

![File Renamer em funcionamento](screenshot.png)

---

## 📌 Funcionalidades

- Seleção da pasta com os arquivos
- Definição do trecho de texto a ser removido dos nomes
- Renomeação automática de todos os arquivos da pasta
- Listagem dos arquivos renomeados
- Interface simples e direta

---

## 🛠️ Tecnologias

| Tecnologia | Papel |
| --- | --- |
| Python 3 | Linguagem |
| PyQt6 | Interface gráfica |
| Módulo `os` | Manipulação de arquivos |

---

## ▶️ Como rodar

```bash
pip install pyqt6
python renomeador.py
```

---

## 🚀 Como usar

1. Abra a aplicação.
2. Selecione a pasta onde estão os arquivos.
3. Digite o texto que deseja remover dos nomes.
4. Clique em **Renomear arquivos**.
5. Confira a lista de arquivos renomeados.

> ⚠️ A renomeação é aplicada diretamente no disco e **não tem desfazer**. Teste em uma cópia da pasta antes de usar em arquivos importantes.

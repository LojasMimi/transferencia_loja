

# 📦 Transferência entre Lojas - Aplicativo Streamlit

Este é um aplicativo web desenvolvido com **Streamlit** para facilitar o processo de **transferência de produtos entre lojas**. O sistema permite que os usuários gerem formulários de transferência de forma individual ou em lote, além de realizar a conferência de recebimentos de forma prática e automatizada.

---

## 🚀 Funcionalidades

* 🔄 **Selecionar lojas de origem e destino**
* 📑 **Carregar planilhas de produtos automaticamente a partir de uma pasta local**
* 📝 **Preencher formulários de transferência individualmente ou em lote (via upload)**
* 📤 **Gerar relatórios em Excel prontos para impressão**
* ✅ **Conferir recebimentos com base nos formulários preenchidos**

---

## 📁 Estrutura de Pastas

```
.
├── propotipo_git_transferencia.py
├── planilhas/                  # Coloque aqui as planilhas de produtos (.xlsx ou .xls)
├── FORMULÁRIO DE TRANSFERENCIA ENTRE LOJAS.xlsx  # Template usado para gerar os formulários
├── requirements.txt            # Dependências do projeto
```

---

## ⚙️ Como Rodar o Projeto

1. **Clone este repositório:**

```bash
git clone https://github.com/LojasMimi/transferencia_loja.git
cd transferencia_loja
```

2. **Instale as dependências:**

```bash
pip install -r requirements.txt
```

3. **Execute o aplicativo:**

```bash
streamlit run propotipo_git_transferencia.py
```

5. **Acesse no navegador:**

Abra [http://localhost:8501](http://localhost:8501) no navegador.

---

## 📌 Requisitos

* Python 3.8 ou superior
* Streamlit
* Pandas
* OpenPyXL

Use o arquivo `requirements.txt` para instalar tudo com um só comando.

---

## 📄 Modelo de Formulário

O template **`FORMULÁRIO DE TRANSFERENCIA ENTRE LOJAS.xlsx`** deve estar presente na raiz do projeto. Ele é usado como base para geração dos relatórios de transferência.

---

## 🛠️ Desenvolvimento

Este projeto foi desenvolvido por **Pablo** para as lojas **MIMI** com o objetivo de tornar o processo de controle de transferências mais ágil, confiável e digital.

---

## 📬 Contato

Se tiver dúvidas, sugestões ou quiser contribuir, fique à vontade para abrir uma *issue* ou entrar em contato.

---

## 📝 Licença

Este projeto é privado e de uso exclusivo das lojas **MIMI**.



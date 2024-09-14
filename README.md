# PDF-Data-Extraction

## 📄 Summary

The extracted data is considered **unstructured data** because it does not follow a fixed or standardized format, like that of a traditional database. It comes in various forms, such as text within PDFs, where the information may be organized differently in each document. To make the data usable, it requires **extraction, processing, and cleaning techniques** to convert it into a structured format that can be analyzed and validated.

Os dados extraídos das notas fiscais são considerados **dados não estruturados** porque não seguem um formato fixo ou padronizado, como o de um banco de dados tradicional. Eles vêm em formatos variados, como texto dentro de PDFs, onde as informações podem estar organizadas de maneiras diferentes em cada documento. Para torná-los utilizáveis, é necessário aplicar **técnicas de extração, processamento e limpeza** para convertê-los em um formato estruturado que possa ser analisado e validado.

---

## 📚 Contents

### 🛠 Test Code: `Notas_Final.ipynb`

### 📑 Code One: `Notas_Final_2_multiplas_notas.ipynb`

- **Extracts data from PDF files** using libraries such as `pdfplumber`.
- **Cleans the extracted data** to ensure accuracy and consistency.
- **Identifies and retrieves values** for quantity and unit price from the invoices.
- **Collects the NCM (Mercosur Common Nomenclature) column** to verify item eligibility for financing via the BNDES Finame website.
- **Sums up the values** of financed items directly for further analysis.

---

## Primeiro Código:

- **Extrai dados de arquivos PDF** usando bibliotecas como `pdfplumber`.
- **Limpa os dados extraídos** para garantir a precisão e consistência.
- **Identifica e recupera os valores** de quantidade e preço unitário das notas fiscais.
- **Coleta a coluna NCM** (Nomenclatura Comum do Mercosul) para verificar a elegibilidade de itens financiáveis através do site do BNDES Finame.
- **Soma diretamente os valores** dos itens financiáveis para posterior análise.


---

**Next Step:** Create a process to extract the total value of each invoice and compare it with the result of multiplying the unit value by the quantity, performing a validation of the results.

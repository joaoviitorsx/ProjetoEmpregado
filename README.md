# Extrator de FGTS

Uma aplicação desktop desenvolvida para automatizar a extração de dados de FGTS a partir de arquivos PDF, facilitando o trabalho contábil.

## Funcionalidades

- **Extração de PDFs individuais**: Processe um único arquivo PDF com dados de FGTS
- **Processamento em lote**: Extraia dados de múltiplos PDFs em uma pasta
- **Reconhecimento automático**: Detecta matrícula, nome, CPF, admissão, base e valor do FGTS
- **Validação de dados**: Verificação automática para garantir consistência das informações
- **Exportação para Excel**: Gera planilhas organizadas por competência com formatação adequada
- **Interface amigável**: Design moderno e responsivo para facilitar o uso

## Pré-requisitos

- Python 3.8 ou superior
- Bibliotecas:
  - PySide6
  - PyMuPDF (fitz)
  - pdfplumber
  - pandas
  - openpyxl


## Tecnologias Utilizadas

- **PySide6**: Interface gráfica moderna e responsiva
- **PyMuPDF/pdfplumber**: Extração de texto de documentos PDF
- **Pandas/Openpyxl**: Manipulação de dados e geração de planilhas
- **Expressões Regulares**: Reconhecimento de padrões nos documentos


© 2025 - Todos os direitos reservados.

# PDF Splitter Plus

**PDF Splitter Plus** é uma ferramenta para dividir arquivos PDF em múltiplos documentos com base em um texto específico. Além disso, permite extrair e mover páginas de capa para uma pasta separada, se necessário. A aplicação é desenvolvida em Python utilizando bibliotecas como PyPDF2, PyMuPDF (fitz) e Tkinter para a interface gráfica.

## Funcionalidades

- **Divisão de PDF:** Divide o PDF em arquivos separados com base em um texto específico encontrado nas páginas.
- **Extração de Páginas de Capa:** Permite extrair páginas específicas para um arquivo de capa separado.
- **Interface Gráfica:** Fornece uma interface gráfica amigável para selecionar arquivos, definir parâmetros e acompanhar o progresso.

## Requisitos

Certifique-se de que você tenha as seguintes bibliotecas instaladas:

- `PyPDF2`
- `PyMuPDF` (fitz)
- `tkinter` (incluído por padrão com Python)

Instale as bibliotecas necessárias com pip:

```bash
pip install PyPDF2 pymupdf
````

Uso
1 Execute o Script: Abra o terminal e execute o script:

```bash
python nome_do_arquivo.py
````

2 Selecione os Arquivos PDF: Clique no botão "Selecionar Arquivos" e escolha os arquivos PDF que deseja processar.

3 Defina os Parâmetros:

Nome da Concessionária: Insira o nome da concessionária para nomear os arquivos gerados.
Texto para Dividir as Faturas: Informe o texto que será usado para dividir o PDF.
O Arquivo Possui Capa(s): Marque esta opção se o arquivo PDF tiver páginas de capa que você deseja extrair.
Número de Capas: Informe o número de páginas de capa a serem extraídas.
Número da Página da Capa X: Para cada página de capa, insira o número da página correspondente.

4 Inicie o Processo: Clique no botão "Iniciar" para começar a divisão e extração do PDF. O progresso será mostrado na barra de progresso.

Logs
O script gera um arquivo de log chamado operation_log.txt onde todas as operações e erros são registrados.

Exemplo
Aqui está um exemplo de uso do PDF Splitter Plus:

Selecione um arquivo PDF.
Defina o nome da concessionária como Concessionaria ABC.
Insira o texto para divisão como Fatura.
Marque a opção para páginas de capa, insira o número de capas e as páginas correspondentes.
Clique em "Iniciar" para dividir o PDF e extrair as capas.
Contribuição
Se você deseja contribuir para o desenvolvimento do PDF Splitter Plus, fique à vontade para fazer um fork do repositório e enviar pull requests com melhorias e correções.

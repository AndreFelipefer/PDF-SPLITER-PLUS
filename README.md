# PDF Splitter Plus

**PDF Splitter Plus** é uma ferramenta fácil de usar para dividir arquivos PDF em partes menores e extrair páginas de capa para uma pasta separada. Ideal para quem precisa organizar documentos grandes de maneira eficiente.

## Funcionalidades

- **Divisão de Arquivos PDF**: Separa arquivos PDF com base em um texto específico para criar documentos menores.
- **Extração de Páginas de Capa**: Extrai e move páginas de capa para um diretório separado.
- **Interface Gráfica Intuitiva**: Simples e amigável, permitindo fácil configuração e controle.
- **Barra de Progresso em Tempo Real**: Acompanhe o progresso do processamento dos arquivos.
- **Atualização Automática da Contagem de Arquivos**: Mostra o total de arquivos divididos após o processamento.
- **Seleção de Múltiplos Arquivos**: Permite processar vários arquivos PDF simultaneamente.
- **Configuração de Páginas de Capa**: Define o número e as páginas das capas a serem extraídas.

## Aprimoramentos

- **Registro de Operações**: Sistema de log para rastrear operações e erros.
- **Processamento em Segundo Plano**: Utiliza threads para manter a interface responsiva.
- **Atualização Dinâmica da Interface**: Atualiza campos e a barra de progresso em tempo real.
- **Verificação de Dados de Entrada**: Valida dados fornecidos pelo usuário para garantir precisão.
- **Melhoria na Usabilidade**: Ajusta visibilidade de campos e opções para uma melhor interação.
- **Feedback Imediato**: Mensagens de alerta e confirmação informam o status do processamento.

## Como Usar

1. **Selecionar Arquivos**:
   - Clique no botão para escolher arquivos PDF. Você pode selecionar múltiplos arquivos ao mesmo tempo.

2. **Definir Informações**:
   - Insira o nome para os novos arquivos divididos e o texto usado para a divisão.

3. **Configurar Páginas de Capa** (opcional):
   - Se houver capas, marque a opção correspondente e informe os números das páginas de capa.

4. **Iniciar o Processo**:
   - Clique no botão "Iniciar" para começar a divisão e extração. Acompanhe o progresso na barra de progresso.

5. **Visualizar Resultados**:
   - Após o processamento, veja a contagem total de arquivos divididos e acesse os arquivos gerados.

## Dependências

- `os`
- `shutil`
- `PyPDF2`
- `fitz` (PyMuPDF)
- `tkinter`
- `threading`

## Instalação

Para usar o **PDF Splitter Plus**, clone este repositório e instale as dependências necessárias. 

```bash
git clone https://github.com/usuario/pdf-splitter-plus.git
cd pdf-splitter-plus
pip install -r requirements.txt

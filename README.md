# RecohecimentoPlacasCarros
Projeto para reconhecimento de placas e uma simples consulta em um banco de dados local.


### Bibliotecas necessárias:
1. pip install numpy
2. pip install opencv-python
3. pip install imutils
4. pip install pytesseract
5. pip install tesseract-ocr
6. pip install pandas

### Problemas com pytesseract no Windows

Pode-se instalar uma versão antiga 3.02 disponível para Windows no link <https://sourceforge.net/projects/tesseract-ocr-alt/files/>. Com dados de treinamento em inglês. Se você deseja usar outro idioma, faça o download dos dados de treinamento apropriados, descompacte-os usando 7-zip e copie o arquivo **.traineddata** no diretório **'tessdata'**, provavelmente C: \ Arquivos de Programas\tesseract-OCR\tessdata.

Para acessar o tesseract-OCR a partir de qualquer local, pode ser necessário adicionar o diretório em que os binários do tesseract-OCR estão localizados às variáveis Path, provavelmente C:\Arquivos de Programas\Tesseract-OCR.

É preciso também no código passar o endereço que o 

pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe' 

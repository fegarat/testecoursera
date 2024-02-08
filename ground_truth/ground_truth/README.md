# Instruções

Será utilizada a ferramenta [LabelMe](https://github.com/labelmeai/labelme) para fazer as anotoções.


## Instalando a ferramenta
É necessário que computador tenha o Anaconda já instalado.

```bash
conda create --name=labelme python=3
conda activate labelme
pip install labelme
```

Exista ainda a possibilidade de baixar um instalar da ferramenta na página de [Releases do Github](https://github.com/labelmeai/labelme/releases).


## Passo a passo

1. Abrir ferramenta
2. Clicar no botão "open dir"
3. Seleciona a subpasta do projeto "ground_truth"
4. Buscar por cnpjs, valores monentários e datas.
5. Ctrl+R para ativar a criação de retângulos.
6. Começa a marcar no quanto superior esquerdo do objeto e termina no inferior direito.
7. Quando abrir a janelinha, no primeiro campo escrever o nome da classe: "cnpj", "data" ou "moeda" (sem aspas).
8. No último campo de texto, escrever o texto literal que será utilizado como referência. É exatamento que aparece no documento.

Para ajudar salvei um vídeo de passo a passo nessa pasta. 
- [passo_a_passo_labelme.webm](passo_a_passo_labelme.webm)

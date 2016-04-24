# Scoop | Bucket com ferramentas gráficas
Bucket para o instalador de softwares CLI Scoop, com *app manifests* de ferramentas open source para trabalhos gráficos.

Para maiores informações sobre a ferramenta Scoop, acesse o site oficial http://scoop.sh/.

## Instalação do Bucket
Através do seu terminal, adicione este bucket ao seu Scoop através do seguinte comando:

`λ scoop bucket add graphic-tools https://github.com/thiagotelespereira/scoop-bucket-graphic-tools.git`

>**Nota**
>
>Neste exemplo eu utilizei o termo *graphic-tools* para nomear este bucket, porém você pode nomear com o termo que desejar.

Após a instalação, execute o seguinte comando para verificar se o bucket já está presente no diretório do Scoop:

`λ scoop bucket list`

Se o nome que você deu ao bucket aparecer na lista, você já está apto a instalar os apps contidos neste bucket.

## Instalando os Apps
A sintaxe do Scoop para instalar um app é a seguinte:

`λ scoop install <nome_do_app>`

### Apps
Listagem de todos os apps contidos neste bucket.

|App     |comando                    |
|--------|---------------------------|
|Inkscape|`scoop install inkscape`   |

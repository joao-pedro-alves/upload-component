##  UploadComponent
Classe de upload de arquivos para o cakePHP. 

--

##### *UploadComponent*::dir

Direitorio a ser salvo

--


##### *UploadComponent*::chagedir(*String* $dir)
 
Muda o direito atual a ser salvo

--

##### *UploadComponent*::trueFile(*File* $file)

Retorna o verdadeiro Array do arquivo

--

##### *UploadComponent*::file(*File* $file)

Seta o arquivo atual

--

##### *UploadComponent*::clear()

Limpa as variaveis e remove o arquivo sendo usado

--

##### *UploadComponent*::delete(*String* $name = *UploadComponent*::file, *String* $dir)

  - **$name** Nome do arquivo
  - **$dir** Direito do arquivo

Deleta um arquivo no diretorio atual

--

##### *UploadComponent*::fileType(*File* $file)

Retorna o tipo do arquivo

--

##### *UploadComponent*::uploadImg(*File* $file, *Array* $params)
 - *Array** *$params**
    * *Array* Resize
        * *Integer* width
        * *Integer* height
        * *String* cover
    * *String* Name
    * *String* Quality
    
--

##### *UploadComponent*::able( *File* $file, *Boolean* $msg = false, *Array* $ext)
 - **$file** Arquivo a ser verificado
 - **$msg**  Retornar uma messagem ou Boolean
 - **$ext**  Array com tipos de aquivo aceitos

--

##### *UploadComponent*::resize(*Integer* $w, *Integer* $h, *Integer* $x, *Integer* $y, *Boolean* $cover=false)
 - **$w** Largura da imagem
 - **$h** Altura da image
 - **$x** Nova Largura
 - **$y** Nova Altura
 - **$cover** Cortar a imagem

Retorna um array com novo W, H, X, Y

--

##### Contribuidores

  - Vinicius Pacheco

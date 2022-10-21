Abra a pasta do projeto e selecione a opção git bash
<br>
-- git init
<br>
Use o comando acima para iniciar o Git, e o proximo comando para enviar os arquivos para uma area de espera <br>
-- git add . <br>
-- git add "arquivo.algo"
<br>
Use o proximo comando sempre que quiser verificar se os arquivos estão corretamente. <br>
-- git status
<br>
Para comentar as alterações realizadas use o proximo comando <br>
-- git commit -m "comentario"
<br>
Agora, se for a primeira vez que você envia um arquivo para esse repositorio. Você usar um comando para conectar o git ao repositorio do github <br>
-- git remote add origin caminhoDoRepositorio
<br>
git: usamos o com os comandos git <br>
remote: faz a ligação do local com o github <br>
add: adiciona o arquivo <br>
origin: nome que estamos dando para esse caminho <br>
-- git push -u origin main
<br>
Irá dar aquele empurrão nos arquivos para enviar eles para o github <br>
Após isso, estando no mesmo projeto, as alterações podem ser feitas apenas com: <br>

-- git add . <br>
-- git git status <br>
-- git commit -m "comentario" <br>
-- git push || -- git push origin main

-Colocar explicação sobre Branch-
<br> <br>
Para trocar da branch main para uma nova e inexistente, usamos o comando: <br>
-- git checkout -b "nova-branch"

Agora para subir os arquivos na nova branch, deve se seguir os mesmos passos de sempre: <br>
-- git add . <br>
-- git status <br>
-- git commit -m "comentario" <br>
-- git push origin nova-branch

Caso queria trocar para a branch do main ou para alguma outra existente <br>
-- git checkout main <br>
-- git checkout outra-branch-existente

-Colocar explicação sobre como funciona o merge-

Para fazer um merge é preciso estar no main, então após verificar que está no main, basta:
<br>
-- git merge nova-branch <br>
-- git push origin main

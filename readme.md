cambios estados y detalle
git status -> ayuda a ver el estado de mi proyecto para git
git diff -> ver los cambios a detallegit

--para subir
git add . -> agrega todos los cambios "nombre archivo " solo el archivo
git commit -m "mensaje"-> confirmas el cambio que vas a subir -m con un mensaje(mejor siempre usar describe la operacion)
git push -> sube los cambios a git remoto

--para bajar
git fetch -> trae los cambios al local sin fusionarlos
git merge -> fusiona los cambios del remoto al local
git pull -> realiza todo de golpe (fetch y merge) pero puede ROMPER CAMBIOS O PISARLOS

@requestmapping("/listar")
serviciolista(){
claseFunciones.listar-cuentas();
updateEstados();
InsertAuditoria();
}

funcion listar-cuentas(){
listad= listad;
}

funcion updateEstados(){
update lista de sus estados;
}

funcion InsertAuditoria(){
insert auditoria;
}

GIT CHECKOUT BORRAR CAMBIOS  
GIT checkout dev -> git branch dev

git log -> vez el historial del git en local

aqui cambios de otro user

git reset HEAD^ --hard -> elimina el ultimo commit en local
git push origin -f -> sube los cambios forzando el push

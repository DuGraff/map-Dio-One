# map-Dio-One
projeto map Dio . 

function getAdmins(Map){
let Admins =[]
for([Key , value ] of map){
if(value === 'Admin'){
    Admins.push(key)
}
}
return Admins;
}

const usuarios =new Map ();
usuarios.set ('luis' ,' Admin');
usuarios.set ('Edu' ,' Admin');
usuarios.set ('Ana' ,' user');
usuarios.set ('Addo' ,' Admin');

console.log(get.Admins(usuarios));

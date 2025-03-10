# SPODW2_AULA1

atv1: let piramide = "";

for (let i = 0; i < 7; i++) {
    console.log(piramide += 'X');   
}

atv2: function mostraXadrez(num){
    let output = "";
    for(let i = 0; i < num; i++){
        output += "# ";
    }
    for (let i = 0; i < num; i++){
        if (i % 2 == 1)
            console.log(output);
        else
            console.log(" " + output);
    }
}

mostraXadrez(8);

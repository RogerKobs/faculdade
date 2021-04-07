# faculdade
Trabalhos da faculdade

<h1>Filter</h1>
Serve para criar uma cópia de um array.
</br>
ex:

```
let arr = ["Roger", "Gabriel", "Schneider", "Kobs];
let resultado = arr.filter(valor => arr);

resultado // ["Roger", "Gabriel", "Schneider", "Kobs].
```

Também é possível você pegar apenas itens com uma quantidade de caracteres.
ex:

```
resultado = arr.filter(valor => arr.length >= 6)

resultado // ["Gabriel", "Schneider"].
```

</br>
</br>

<h1>ForEach</h1>
um For que você roda até percorrer todos os itens de um array.
ex:

let arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

arr.forEach(resultado => console.log(5 * resultado))
// 5
// 10
// 15
...



Join - concatena todos os valores de um array conforme a vontade do usuario.

const arr = ["Roger", "Gabriel", "Schneider", "Kobs"]

ex: dando espaço
arr.join(" ") // Roger Gabriel Schneider Kobs

separando com ponto:
arr.join("-") // Roger.Gabriel.Schneider.Kobs



LastIndexOf - conta quantas letras tem antes da palavra ou letra desejada, se caso tiver mais de um ele pega a ultima.
ex:
let palavra = "Isso é um teste"
palavra.lastIndexOf("e") // 14



IndexOf - informa o index da palavra ou letra solicitada, caso não encontre retorna -1.

const arr = ["Roger", "Gabriel", "Schneider", "Kobs"]

arr.indexOf("Roger") // 0
arr.indexOf("Silva") // -1



Map - percorre uma lista no mesmo estilo do forEach, só que já executando uma função de callback.

const arr = ["Roger", "Gabriel", "Schneider", "Kobs"]

arr.map(valor => { console.log(valor) })
// Roger
// Gabriel
// Schineider
// Kobs

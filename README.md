# Object

//1. feladat
let pi = {
    height: 165,
    name: {
        first: 'Sallemi',
        last: 'Biagia',
    },
};

const { height } = pi;
console.log(height)


//2. feladat
const { name } = pi
console.log(name)

//3. feladat
let fta = ['snake, fox, wolf']
console.log(fta)

//4.feladat
console.log(Object.keys(pi))

//5.feladat
console.log(Object.values(pi))

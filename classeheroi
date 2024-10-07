// Classe que representa um herói
class Heroi {
    // Construtor que define as propriedades da classe
    constructor(nome, idade, tipo) {
        this.nome = nome;  // Nome do herói
        this.idade = idade; // Idade do herói
        this.tipo = tipo;   // Tipo do herói (guerreiro, mago, etc.)
    }

    // Método para o herói atacar, com base no tipo
    atacar() {
        let ataque;

        // Estrutura de decisão para escolher o tipo de ataque
        if (this.tipo === "mago") {
            ataque = "usou magia";
        } else if (this.tipo === "guerreiro") {
            ataque = "usou espada";
        } else if (this.tipo === "monge") {
            ataque = "usou artes marciais";
        } else if (this.tipo === "ninja") {
            ataque = "usou shuriken";
        } else {
            ataque = "fez um ataque desconhecido";
        }

        // Exibe a mensagem com o tipo e o ataque correspondente
        console.log(`O ${this.tipo} atacou usando ${ataque}`);
    }
}

// Exemplo de criação de objetos e teste do método atacar

// Criando um objeto do tipo mago
const heroi1 = new Heroi("Merlin", 150, "mago");
heroi1.atacar();  // Saída: O mago atacou usando magia

// Criando um objeto do tipo guerreiro
const heroi2 = new Heroi("Arthas", 30, "guerreiro");
heroi2.atacar();  // Saída: O guerreiro atacou usando espada

// Criando um objeto do tipo monge
const heroi3 = new Heroi("Shaolin", 40, "monge");
heroi3.atacar();  // Saída: O monge atacou usando artes marciais

// Criando um objeto do tipo ninja
const heroi4 = new Heroi("Naruto", 25, "ninja");
heroi4.atacar();  // Saída: O ninja atacou usando shuriken

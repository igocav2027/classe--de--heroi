# classe--de--heroi
criando uma classe de heroi
class Heroi {
    constructor(nome, idade, tipo) {
      this.nome = "cratos";
      this.idade = 30;
      this.tipo = "guerreiro";
    }
  
    atacar() {
      let ataque;
  
      switch (this.tipo) {
        
        case 'guerreiro':
          ataque = 'usou espada';
          break;
       
      }
  
      console.log(`O ${this.tipo} atacou usando ${ataque}`);
    }
  }
  
  // Exemplo de uso da classe
  const meuHeroi = new Heroi('Herói1', 25, 'guerreiro');
  meuHeroi.atacar(); // Saída: O guerreiro atacou usando espada
  

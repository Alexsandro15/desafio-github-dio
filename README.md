# desafio-github-dio
Lista de perguntas e desafios de C#

# Exercícios
## Sintaxe básica
### Informações básicas
1) Qual a principal diferença entre o .NET Framework e o .NET (a partir da versão 3.1)?
A) .NET Framework é multiplataforma; .NET não.
B) .NET é voltado exclusivamente para jogos.
C) .NET Framework funciona apenas no Windows; .NET é multiplataforma.
D) Não há diferença — são nomes equivalentes.

2) O que é o .NET Standard?
A) Um sistema de compilação que converte código em linguagem binária.
B) Um padrão para garantir que as bibliotecas funcionem em diferentes versões e plataformas do .NET.
C) Um tipo especial de IDE usado para desenvolver APIs REST.
D) Uma versão inicial da linguagem C# voltada para JavaScript.

3) No processo de compilação do C#, qual a função do JIT (Just-In-Time Compiler)?
A) Corrigir erros de lógica automaticamente
B) Gerar o código-fonte do programa
C) Traduzir o código intermediário em código de máquina na hora da execução
D) Criar a interface gráfica da aplicação

4) Qual das opções não é uma vantagem do Visual Studio Code comparado ao Visual Studio tradicional?
A) Funciona no Linux
B) É mais leve
C) Não requer instalação de extensões para funcionar completamente
D) Gratuito

5) O comando dotnet new console é usado para:
A) Rodar um programa já compilado no terminal
B) Criar uma nova interface gráfica com botões e janelas
C) Criar um novo projeto de console com entrada e saída no terminal
D) Atualizar o SDK do .NET instalado na máquina

6) Qual a funcionalidade da extensão “C# Extensions” no VS Code?
A) Criar arquivos de banco de dados automaticamente
B) Compilar código Python dentro do Visual Studio
C) Ajudar na criação de classes, interfaces e outros componentes C#
D) Rodar comandos PowerShell diretamente pelo terminal

## Sintaxe básica
1) O que é namespace em C#?
A) Um tipo de variável global
B) Um diretório físico onde os arquivos são salvos
C) Um agrupador lógico de classes e interfaces
D) Um comando de compilação

2) Qual das opções abaixo cria corretamente um objeto da classe Pessoa?
A) Pessoa = new Pessoa();
B) Pessoa pessoa = Pessoa();
C) new Pessoa pessoa = Pessoa();
D) Pessoa pessoa = new Pessoa();

3) Qual a diferença entre string e char em C#?
A) string armazena números e char armazena letras
B) string armazena uma letra e char armazena várias
C) string armazena várias letras e char armazena um único caractere
D) Não há diferença

4) O que significa public string Nome { get; set; } em uma classe?
A) Um método público
B) Um atributo protegido
C) Um atributo com acesso público com métodos automáticos de leitura e escrita
D) Um método que retorna uma string

5) Qual comando compila e executa um programa C# no terminal usando .NET?
A) dotnet start
B) dotnet run
C) csc run
D) run program.cs

6) O que a seguinte linha faz?
Console.WriteLine($"Olá {nome}");
A) Cria uma variável chamada Olá
B) Exibe o texto “Olá nome” na tela
C) Exibe o conteúdo da variável nome junto com “Olá”
D) Cria uma string com nome “Olá”

7) Qual o efeito de Trim() em uma string?
A) Remove todas as letras da string
B) Adiciona espaços em branco no início e fim
C) Remove espaços no início e no fim da string
D) Transforma a string em letras maiúsculas

8) Qual das opções abaixo representa um tipo de dado usado para valores decimais com alta precisão?
A) int
B) double
C) decimal
D) char

9) O que significa DateTime.Now?
A) Cria uma nova data no futuro
B) Obtém o tempo atual do sistema
C) Apaga o horário atual
D) Converte uma string para data

10) Qual o objetivo do método DateTime.TryParseExact()?
A) Converter uma string em número decimal
B) Criar arquivos com data e hora
C) Testar se uma string está no formato correto de data
D) Exibir o dia atual no formato brasileiro

11) Qual é a saída do código abaixo?
int a = 5;
a += 3;
Console.WriteLine(a);

A) 8
B) 5
C) 3
D) 15

12) Qual das opções converte corretamente uma string para inteiro?
string numero = "42";
A) int resultado = numero.Parse();
B) int resultado = Convert.ToInt32(numero);
C) int resultado = ToInt(numero);
D) int resultado = numero.ToInt();

13) O que será impresso?
int x = 10;
int y = 3;
Console.WriteLine(x % y);

A) 3
B) 1
C) 0
D) 10

14) Qual o valor da variável resultado?
int a = 2;
int b = 3;
int resultado = (a + b) + 2 * 5;

A) 5
B) 10
C) 15
D) 12

15) O que o seguinte código faz?
double numero = 16;
Console.WriteLine(Math.Sqrt(numero));

A) Calcula o quadrado de 16
B) Calcula o dobro de 16
C) Calcula a raiz quadrada de 16
D) Retorna erro

16) O que é o arquivo .csproj em um projeto C#?
A) Código principal do sistema
B) Responsável por gerenciar o banco de dados
C) Arquivo de configuração do projeto, como versão e dependências
D) Arquivo que armazena os dados do usuário

17) Dado o seguinte código:
int x = 2;
int y = 3;
double resultado = Math.Pow(x, y);

Qual será o valor armazenado na variável resultado?
A) 6
B) 8
C) 9
D) 5

18) Qual método da biblioteca Math para arredondar um número?
A) Math.Pow()
B) Math.Sqrt()
C) Math.Round()
D) Math.Root()

19) Qual a função do arquivo .csproj em um projeto C#?
A) Armazenar dados do banco
B) Gerenciar múltiplos projetos
C) Controlar referências entre projetos
D) Configurar o build e informações do projeto

20) Assinale a afirmativa correta:
A) .sln não é necessário em projetos C#
B) .sln carrega configurações de um único projeto
C) .sln armazena referências entre múltiplos projetos
D) .csproj substitui o .sln em projetos grandes

21) Para adicionar um projeto C# a uma solução .sln, qual comando usamos?
A) dotnet add sln reference
B) dotnet sln add projeto.csproj
C) dotnet connect csproj
D) dotnet new project –add

22) O que será impresso no console?
int[] numeros = { 5, 10, 15, 20 };
Console.WriteLine(numeros[2]);

A) 5
B) 10
C) 15
D) 20

23) Qual das opções abaixo causará erro?
int[] numeros = new int[3];
numeros[0] = 10;
numeros[1] = 20;
numeros[2] = 30;

A) numeros[2] = 30;
B) numeros[3] = 40;
C) Console.WriteLine(numeros[1]);
D) Console.WriteLine(numeros.Length);

24) Qual é a saída do código abaixo?
string[] nomes = { "Ana", "Bruno", "Carlos" };
foreach (string nome in nomes)
{
    Console.Write(nome + " ");
}

A) Ana Bruno Carlos
B) Ana, Bruno, Carlos
C) Bruno Carlos
D) Carlos Bruno Ana

25) O que acontece ao executar este código?
int[] numeros = { 1, 2, 3 };
Array.Resize(ref numeros, 5);
Console.WriteLine(numeros.Length);

A) Erro de compilação
B) O array continua com tamanho 3
C) O array agora tem tamanho 5
D) O array agora tem tamanho 4

26) Qual alternativa copia corretamente um array?
int[] origem = { 1, 2, 3 };
int[] destino = new int[3];
???

A) Array.Copy(origem, destino, 2);
B) Array.Copy(destino, origem, 3);
C) Array.Copy(origem, destino, 3);
D) Array.Copy(origem);

28) O que está incorreto neste trecho?
List<string> lista = new List<string>() { "A", "B", "C" };
foreach (string item in lista)
{
    Console.WriteLine(lista[item]);
}

A) Lista está correta
B) Foreach está incorreto
C) O acesso lista[item] está incorreto
D) Tudo está correto

29) O que acontece neste código?
var tupla = (nome: "Maria", idade: 22);
tupla.idade = 23;

A) Idade é atualizada
B) Compila, mas dá erro em tempo de execução
C) Erro de compilação
D) Retorna null

## Exercícios práticos
1) Criar um programa console que recebe uma descrição de tarefa, trata o texto, analisa a presença de certas palavras(‘fazer’ trocar por ‘executar’, e se tiver urgente, muito urgente ou pouco urgente salve isso), calcula data e hora de execução e mostra todos os dados de forma organizada.
Urgente(pegue o dia de hj e adicione 5 dias), pouco urgente(adicione 2 dias) e muito urgente(adicione 10 dias)
Mostre dia de execução, 
Nome da tarefa,
urgencia

2) O programa deve receber uma lista de números digitados pelo usuário(pelo menos 4), analisar os dados com cálculos matemáticos, e apresentar resultados como:
valor máximo,
média,
raiz quadrada de cada valor,
verificação se são pares ou ímpares,
e aplicação de operadores condicionais com if e for etc.
pegue os números como string e converta decimal
para depois salvar em um array

3) O objetivo é armazenar nomes e notas de alunos usando listas e tuplas, fazer alguns cálculos com arrays, manipular os dados, e exibir resultados organizados. Você vai praticar:
•  Crie duas listas:
•	Uma lista de nomes dos alunos (List<string>)
•	Uma lista de notas dos alunos (List<double>)
•  Peça ao usuário para informar:
•	Quantos alunos deseja cadastrar
•	O nome e a nota de cada um
•  Armazene esses dados em uma tupla por aluno, dentro de um array de tuplas
•  Exiba:
•	Todos os alunos e suas respectivas notas
•	A média das notas
•	A nota máxima e o nome do aluno que a obteve
•	Todos os alunos acima da média
•  Faça uma cópia do array de tuplas original em outro array com dois espaços extras e mostre que os novos espaços estão vazios.

## Manipulando dados e listas + introdução a POO
propriedades, métodos e construtores com c#
using System;
using System.Collections.Generic;

namespace ProjetoCadastro
{
    public class Pessoa
    {
        private string _nome;
        private string _sobrenome;

        // Propriedade com validação e encapsulamento
        public string Nome
        {
            get => _nome.ToUpper();
            set
            {
                if (string.IsNullOrWhiteSpace(value))
                {
                    throw new ArgumentException("Nome não pode ser vazio");
                }
                _nome = value;
            }
        }

        public string Sobrenome
        {
            get => _sobrenome.ToUpper();
            set => _sobrenome = value;
        }

        // Propriedade só de leitura (read-only)
        public string NomeCompleto => $"{Nome} {Sobrenome}";

        // Construtores
        public Pessoa() { }

        public Pessoa(string nome, string sobrenome)
        {
            Nome = nome;
            Sobrenome = sobrenome;
        }

        // Método para imprimir nome completo
        public void MostrarNomeCompleto()
        {
            Console.WriteLine(NomeCompleto);
        }

        // Método deconstrutor (opcional)
        public void Deconstruct(out string nome, out string sobrenome)
        {
            nome = Nome;
            sobrenome = Sobrenome;
        }
    }

    public class Curso
    {
        public string Nome { get; set; }
        public List<Pessoa> Alunos { get; set; } = new List<Pessoa>();

        public void AdicionarAluno(Pessoa aluno)
        {
            Alunos.Add(aluno);
        }

        public bool RemoverAluno(Pessoa aluno)
        {
            return Alunos.Remove(aluno);
        }

        public void ListarAlunos()
        {
            for (int i = 0; i < Alunos.Count; i++)
            {
                Console.WriteLine($"N {i + 1} - {Alunos[i].NomeCompleto}");
            }
        }

        public int ObterQuantidade()
        {
            return Alunos.Count;
        }
    }

    class Program
    {
        static void Main(string[] args)
        {
            // Criando pessoas
            Pessoa aluno1 = new Pessoa("João", "Silva");
            Pessoa aluno2 = new Pessoa("Maria", "Oliveira");
            Pessoa aluno3 = new Pessoa("Lucas", "Almeida");

            // Criando curso e adicionando alunos
            Curso cursoTI = new Curso();
            cursoTI.Nome = "Desenvolvimento em C#";

            cursoTI.AdicionarAluno(aluno1);
            cursoTI.AdicionarAluno(aluno2);
            cursoTI.AdicionarAluno(aluno3);

            // Listando alunos
            cursoTI.ListarAlunos();

            // Mostrando quantidade
            Console.WriteLine($"Total de alunos: {cursoTI.ObterQuantidade()}");

            // Removendo aluno
            cursoTI.RemoverAluno(aluno2);
            Console.WriteLine("\nApós remoção:");
            cursoTI.ListarAlunos();
        }
    }
}

1) O que a propriedade NomeCompleto da classe Pessoa faz?
a) Modifica o nome e o sobrenome diretamente
b) Retorna o nome e o sobrenome em letras minúsculas
c) Retorna o nome e sobrenome em maiúsculas separados por espaço
d) Define os valores de nome e sobrenome automaticamente

2) O que acontece se tentarmos criar uma Pessoa com nome vazio?
a) O programa atribui "Sem nome"
b) O programa continua normalmente
c) É lançada uma exceção
d) O sobrenome é apagado

3) Qual a principal função do construtor Pessoa(string nome, string sobrenome)?
a) Criar uma nova instância da classe com valores fixos
b) Inicializar propriedades com valores passados ao instanciar
c) Eliminar os valores de nome e sobrenome
d) Criar um método com sobrecarga

4) O que a linha public string Nome { get => _nome.ToUpper(); set {...} } significa?
a) O valor do nome sempre será convertido para minúsculo
b) O nome será armazenado em maiúsculas no _nome
c) O nome será retornado em maiúsculas, mas armazenado como foi digitado
d) Não altera nada na string

5) Qual a vantagem de usar List<Pessoa> Alunos em vez de criar várias variáveis individuais?
a) Permite organizar alunos em ordem alfabética
b) Permite usar números no nome dos alunos
c) Permite armazenar múltiplas instâncias dinamicamente
d) Não há nenhuma vantagem real

6) O que o método AdicionarAluno(Pessoa aluno) faz?
a) Cria um novo aluno
b) Remove um aluno da lista
c) Insere o objeto passado na lista de alunos
d) Exibe o nome do aluno

7) Se cursoTI.ObterQuantidade() retornar 2, isso significa que:
a) A lista está vazia
b) A lista contém dois nomes de cursos
c) Há dois objetos Pessoa na lista Alunos
d) Foram adicionados dois cursos ao aluno

8) Qual o papel do método MostrarNomeCompleto() na classe Pessoa?
a) Imprimir nome e sobrenome convertidos para minúsculo
b) Exibir NomeCompleto formatado em uma linha
c) Retornar uma string com o nome do curso
d) Criar uma nova pessoa

9) O que o Deconstruct faz na classe Pessoa?
a) Deleta a pessoa da memória
b) Extrai nome e sobrenome como variáveis separadas
c) Cria uma nova pessoa com base em outra
d) Remove o sobrenome da propriedade

10) Se eu quiser criar uma Pessoa sem definir os valores imediatamente, qual construtor devo usar?
a) Pessoa(string nome)
b) Pessoa()
c) Pessoa(string nome, string sobrenome)
d) Pessoa(int idade)

## Exceções e coleções em c#
1) Qual é a principal utilidade do bloco try-catch em C#?
a) Evitar que o programa use variáveis globais
b) Garantir que os dados sejam salvos em arquivos
c) Lidar com erros e exceções em tempo de execução
d) Melhorar a performance do código

2) O que o bloco finally faz em um try-catch-finally?
a) Só executa se uma exceção for lançada
b) É ignorado caso não haja exceções
c) Executa apenas se o bloco catch for chamado
d) Sempre é executado, com ou sem erro

3) Qual das exceções abaixo é usada especificamente quando um arquivo não é encontrado?
a) Exception
b) FileNotFoundException
c) DirectoryNotFoundException
d) IOException

4) Em uma fila (Queue<int> fila = new Queue<int>()), qual método é usado para adicionar um item?
a) Add()
b) Push()
c) Enqueue()
d) Insert()

5) O que acontece ao chamar fila.Dequeue() em uma Queue<int>?
a) Remove o último item adicionado
b) Remove o primeiro item adicionado
c) Ordena a fila
d) Exclui todos os elementos

6) Em uma pilha (Stack<int>), qual é a ordem correta dos elementos?
a) FIFO (primeiro a entrar, primeiro a sair)
b) LIFO (último a entrar, primeiro a sair)
c) Circular
d) Aleatória

7) Qual método é usado para remover o último item inserido em uma pilha (Stack<int>)?
a) Pop()
b) Dequeue()
c) Remove()
d) Delete()

8) Qual é o tipo correto de declaração para um dicionário com chave string e valor string?
a) List<string, string>
b) Stack<string, string>
c) Dictionary<string, string>
d) Queue<string, string>

9) Como você pode verificar se uma chave existe no dicionário estados?
a) estados.HasKey("SP")
b) estados.Contains("SP")
c) estados.Exists("SP")
d) estados.ContainsKey("SP")

10) O que acontece se você tentar adicionar uma chave duplicada em um Dictionary<string, string>?
a) A chave antiga será substituída
b) A chave será adicionada normalmente
c) Será lançada uma exceção
d) O valor será atualizado automaticamente


## Exercício prático
1) 2 classes Biblioteca(nome, lista de livros com métodos adicionar, remover, listarlivros e ContarLivros) e Livros(herdando da classe biblioteca, atributos = titulo, autor e Ano de publicação com método MostrarDetalhes() q mostra tudo)
2) Crie um programa que simula um sistema de atendimento com:
•	Uma fila de senhas (Queue<string>)
•	Um dicionário com as senhas e os respectivos nomes dos clientes (Dictionary<string, string>)
•	Uso de tratamento de exceções para lidar com senhas não cadastradas.

## Programação oritentada a objetos
1) O que é abstração na Programação Orientada a Objetos?
A) Ato de esconder atributos privados de uma classe
B) Criar cópias de objetos com valores diferentes
C) Representar entidades e comportamentos do mundo real de forma simplificada

D) Tornar métodos inacessíveis externamente
2) Qual das alternativas melhor representa o objetivo da abstração?
A) Aumentar o número de atributos em uma classe
B) Definir um modelo genérico para objetos similares
C) Evitar que classes herdem comportamentos
D) Permitir múltiplas heranças

3) Encapsulamento serve para:
A) Tornar todos os atributos públicos
B) Esconder a implementação e proteger os dados de acesso indevido
C) Reutilizar código por meio da herança
D) Compartilhar dados entre sistemas externos

4) A herança permite que:
A) Classes compartilhem métodos estáticos entre si
B) Um método seja executado várias vezes
C) Uma classe derive comportamentos e atributos de outra
D) Objetos tenham comportamento imprevisível

5) O polimorfismo permite:
A) A existência de múltiplos métodos com o mesmo nome e funções diferentes
B) A criação de atributos duplicados
C) A definição de uma única classe por projeto
D) A comunicação entre sistemas externos

6) O que caracteriza o polimorfismo por sobrescrita (override)?
A) Uso de atributos com mesmo nome em várias classes
B) Métodos com o mesmo nome e parâmetros diferentes
C) Modificação do comportamento de um método herdado
D) Exclusão de métodos herdados

7) O polimorfismo por sobrecarga (overload) ocorre quando:
A) Um método é duplicado em outra classe
B) Dois métodos possuem o mesmo nome, mas diferentes assinaturas
C) Métodos são chamados por múltiplas threads
D) Uma interface é implementada várias vezes

8) O que define uma classe abstrata?
A) Uma classe que nunca pode ter atributos
B) Uma classe com métodos duplicados
C) Uma classe que serve apenas como modelo e não pode ser instanciada
D) Uma classe com apenas métodos públicos

9) O que é uma interface em POO?
A) Um tipo de herança múltipla que implementa atributos
B) Um recurso gráfico de interação com o usuário
C) Um contrato que define os métodos que uma classe deve implementar
D) Uma estrutura para criar métodos privados em outras classes

10) O que o código a seguir representa?
public class Animal
{
    public virtual void EmitirSom()
    {
        Console.WriteLine("Som genérico");
    }
}

public class Cachorro : Animal
{
    public override void EmitirSom()
    {
        Console.WriteLine("Latido");
    }
}

A) Interface e encapsulamento
B) Herança e polimorfismo por sobrescrita
C) Sobrecarga de operadores
D) Classe estática com métodos abstratos

11) Qual conceito o código a seguir representa?
public class Calculadora
{
    public int Somar(int a, int b)
    {
        return a + b;
    }

    public int Somar(int a, int b, int c)
    {
        return a + b + c;
    }
}

A) Polimorfismo por sobrescrita
B) Encapsulamento de métodos
C) Polimorfismo por sobrecarga (tempo de compilação)
D) Herança múltipla

12) Qual o resultado da execução do método MoverVeiculo abaixo?
public class Veiculo
{
    public virtual void Mover()
    {
        Console.WriteLine("Veículo em movimento.");
    }
}

public class Carro : Veiculo
{
    public override void Mover()
    {
        Console.WriteLine("Carro em movimento.");
    }
}

public void MoverVeiculo(Veiculo v)
{
    v.Mover();
}

Chamando MoverVeiculo(new Carro());, temos:

A) “Veículo em movimento.”
B) “Carro em movimento.”
C) Erro de compilação
D) Nenhuma mensagem será exibida

## Exercício prático
1)
•  Uma classe Pessoa com os atributos Nome e Idade, e um método Apresentar().
•  A classe Pessoa deve permitir que o método Apresentar() possa ser sobrescrito.
•  Uma classe Motorista que herda de Pessoa, com um atributo extra CategoriaCNH. Essa classe deve sobrescrever o método Apresentar() para incluir a categoria da CNH.
•  Uma classe Mecânico, que também herda de Pessoa, com um atributo Especialidade, e também sobrescreve Apresentar() para incluir essa especialidade.
•  Uma classe Caminhao, que não herda de Pessoa, mas representa o veículo da frota. Ela deve ter os atributos Placa e Quilometragem, sendo a quilometragem privada. Só é possível interagir com ela usando os métodos Abastecer(), Rodar() e ExibirQuilometragem().



# Lista-de-Convidados
   
        static void Main(string[] args)
        {
            ListaCovidados lista= new ListaCovidados();
            lista.nome = "";           
            Console.WriteLine("Seja bem vindo ao evento, por gentileza, digite o seu nome completo para verificação na lista de convidados:"  ); 
            Console.ReadLine();
            if (lista.nome === "Simone Fagundes") 
            {
                Console.WriteLine("Seja bem vida, Simone Fagundes! Se prepare para o reconhecimento facial");
            }
            Console.ReadLine();
        }


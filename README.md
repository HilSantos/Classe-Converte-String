# Classe-Converte-String
Exercicios em sala.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ProjetoMenu
{
    public class ClasseConverteString
    {
        private string nome, mnome;

  public string entradaDados()
        { 
            Console.Clear();
            Console.WriteLine("Digite um nome: ");
            nome = Console.ReadLine();
            mnome = nome.ToUpper();
            return mnome;
        }
    }
}

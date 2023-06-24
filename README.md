# Exercicio17_CPP
//Correção (Ou Rascunho) visto em sala de aula

#include<iostream>
#include<stdlib>
#include<stdlib.h>
#include<fstream>
#include<ioman.p>
#include<STDIO.H>

using namespace.std;

struct dados_do_aluno
{
 int nome_do aluno;
 int curso;
 int email;
 float nota1;
 float nota2;

}
void.ler(string_Meuarquivo);


int main(){
int nro;
char nome[30], curso [30];
double n1, n2;

cout<<"informe os dados do aluno; "<<ebdk;
cin>>nro>>nome>>curso>>n1>>n2;

int nro_a
char nome_a[30], curso_a[30];
double n1_a, n2_a;
int flag =o;
  ifstream arq_r("aluno.dat", ios::in);

   float nota1, nota2, media;

    cout << "Nota 1: ";
    cin >> nota1;

    cout << "Nota 2: ";
    cin >> nota2;
    
    
    media = (nota1+nota2+)/2;

while (arq_r>>nro_a>>nome_a>>curso_a>>n1_a>>n2_a){
cout <<"Média: " << media;    
if(nro==nro_a){
   flag = 1;
}
{

printf("Leitura Dos Alunos: n\n");
for(1 = 0; i < Quantidade_Alunos; i++)

 printf("Matrícula do Aluno %d: ", (i + 1));
    scanf("%d", &alunos[i].matricula);
    fflush(stdin);

    printf("Nome do Aluno %d: ", (i + 1));
    gets(alunos[i].mome);

     printf("Nota 1 do Aluno %d: ", (i + 1));
    scanf("%f", &alunos[i].nota1);

    printf("Nota 2 do Aluno %d: ", (i + 1));
    scanf("%f", &alunos[i].nota2);


}
}
arq_r.close();
if(flag==1){
cout<<"já existe um arquivo com esse número..." <<endl;
}else{
ofstream arq_w("alunos.dat", ios::app);
arq_w<<nro<<''<<nome<<''<<curso<<''<<n1<<''<<n2<<endl;
cout<<"Registro incluido no arquivo"<<endl;
arq_w.close();
}

return 0;
}

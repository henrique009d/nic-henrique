# nic-henrique
#include <iostream>
#include <time.h>
#include <string>
#include <stdlib.h>
using namespace std;

class Market{
	public:
		
	void cadastro(){
		
		int a;
		
		cout<<"\nSelecione\t1 - CLIENTE\t2 - PRODUTO\t3 - FORNECEDOR\t4 - DESPESAS: ";
		cin>>a;
		switch (a){
			case 1: (a == 1);{
				
				string cliente, cpf, endereco, telefone;
			
				cout<<"\nNome:";
				cin>>cliente;
				cout<<"Endereço:";
				cin>>endereco;
				cout<<"CPF:";
				cin>>cpf;
				cout<<"Telefone:";
				cin>>telefone;
				cout<<"\nCADASTRO REALIZADO COM SUCESSO";
				
							}break;
			
			case 2: (a == 2);{
				
				string produto, marca, lote;
				
				int validade;
				float preco;
				
				cout<<"\nProduto:";
				cin>>produto;
				cout<<"Marca:";
				cin>>marca;
				cout<<"Validade:";
				cin>>validade;
				cout<<"Preço:";
				cin>>preco;
				cout<<"Lote:";
				cin>>lote;
				cout<<"\nCADASTRO REALIZADO COM SUCESSO";
				
							}break;
			
			case 3: (a == 3);{
				
				string fornecedor; 
				int cnpj;
				
				cout<<"\nNome:";
				cin>>fornecedor;
				cout<<"CNPJ:";
				cin>>cnpj;
				cout<<"\nCADASTRO REALIZADO COM SUCESSO";
				
							}break;
				
			case 4: (a == 4);{
				
				float agua, luz, internet;
				
				cout<<"\nÁgua:";
				cin>>agua;
				cout<<"Luz:";
				cin>>luz;
				cout<<"Internet:";
				cin>>internet;
				cout<<"\nTotal: "<<agua+luz+internet;
				cout<<"\n\nCADASTRO REALIZADO COM SUCESSO";
				
							}break;
			}
		
	}
	
	void consulta(){
		
		int b;
		
		cout<<"\nSelecione\t1 - CLIENTE\t2 - PRODUTO\t3 - FORNECEDOR\t4 - DESPESAS:: ";
		cin>>b;
		switch (b){
			case 1: (b == 1);{
				
				string numero;
		
				cout<<"CPF:";
				cin>>numero;
				
							}break;
			
			case 2: (b == 2);{	
			
				string produto;
				
				cout<<"Produto: ";
				cin>>produto;	
				
							}break;
			
			case 3: (b == 3);{
				
				cout<<"\nNome: Bar Luciana's";
				cout<<"\nCNPJ: 12.025.648/0002 64";
				
							}break;
				
			case 4: (b == 4);{
				
				cout<<"\nÁgua: $104.55";
				cout<<"\nLuz: $207.97";
				cout<<"\nInternet: $155.00";
				
							}break;
			}
		
		}
		
	void vendas(){
		
		int b;
		
		cout<<"\nSelecione\t1 - A VISTA\t2 - A PRAZO: ";
		cin>>b;
		switch (b){
			case 1: (b == 1);{		
		cout<<"\nFEIJAO 1KG - BAIANINHO = $15.99";
		cout<<"\nAÇUCAR REFINADO 1KG - DOCELAR = $2.00";
		cout<<"\nFLOCAO DE MILHO - ESPERANÇA = $1.50";
		cout<<"\nARROZ 1KG - DULLAR = $4.99";
		cout<<"\nTEMPERO BAIANO - ISQUENTA = $1.00";
		cout<<"\nCAFÉ 600G - MELITA = $4.99";
		cout<<"\nLEITE EM PÓ 500G - LASSERENISSIMA = $7.99";
		cout<<"\nFEIJAO PRETO - BAIANINHO = $16.99";
		cout<<"\nAÇUCAR DEMERARA 1KG - DULLAR = $6.99";
							}break;
		
		case 2: (b == 2);{		
		cout<<"\nFEIJAO 1KG - BAIANINHO = $15.99";
		cout<<"\nAÇUCAR REFINADO 1KG - DOCELAR = $2.00";
		cout<<"\nFLOCAO DE MILHO - ESPERANÇA = $1.50";
		cout<<"\nARROZ 1KG - DULLAR = $4.99";
		cout<<"\nTEMPERO BAIANO - ISQUENTA = $1.00";
		cout<<"\nCAFÉ 600G - MELITA = $4.99";
		cout<<"\nLEITE EM PÓ 500G - LASSERENISSIMA = $7.99";
		cout<<"\nFEIJAO PRETO - BAIANINHO = $16.99";
		cout<<"\nAÇUCAR DEMERARA 1KG - DULLAR = $6.99";
						}break;
		}
	}
		
	void estoque(){
				
		cout<<"Feijão 1kg - Baianinho - 5 FARDOS COM 10 EM CADA";
	}
	
	void relatorio(){
		
		int c;
		
		cout<<"\nSelecione\t1 - VENDAS\t2 - COMPRAS: ";
		cin>>c;
		switch (c){
			case 1: (c == 1);{
				
			cout<<"\nVENDA DIARIA: $10.000";
			cout<<"\nVENDA MENSAL: $50.000";
				
							}break;
			
			case 2: (c == 2);{	
			
				cout<<"\nCOMPRA ESTOQUE: $15.000";
				cout<<"\nUTENSÍLIOS: $5.000";
				
							}break;
				}
	}
	
	void nf(){
		
		string name_client, adress;
		
		cout<<"\nNome:";
		cin>>name_client;
		cout<<"CPF:";
		cin>>adress;
		
		cout<<"\n*******************";
		cout<<"\n*******************";
		cout<<"\n*******NOTA FISCAL*******";
		cout<<"\n*******************";
		cout<<"\n*******************";
		cout<<"\nSupermercado Barreto's' LTDA";
		cout<<"\nCNPJ: 36.025.619/0001-06";
		cout<<"\nAV ILTON LOPES LEAL, N°107, VILA ALMEIDA";
		cout<<"\nCEP: 45580 - 001 - Tel: 3537 - 0014";
		cout<<"\nDOCUMENTO AUXILIAR DA NOTA FISCAL DE CONSUMIDOR ELETRÔNICA";
		cout<<"\n\nPRODUTO";
		cout<<"\nPRODUTO";
		cout<<"\nPRODUTO";
		cout<<"\nPRODUTO";
		cout<<"\nPRODUTO";
		cout<<"\nPRODUTO";
		cout<<"\nPRODUTO\n";
		cout<<"\nCPF: "<<adress;
		
		time_t data_tempo;
		time(&data_tempo);
		    
		struct tm*tempo = localtime(&data_tempo);
		struct tm*data = localtime(&data_tempo);
		
		int ano = data->tm_year + 1900;
		int mes = data->tm_mon + 1;
		int dia = data->tm_mday;
		
		int seg = tempo->tm_sec;
		int min = tempo->tm_min;
		int hora = tempo->tm_hour;
		
		cout<<"\nData: "<<dia<<"/"<<mes<<"/"<<ano<<" as "<<hora<<":"<<min<<":"<<seg;
	}
	
	void ajuda(){
		
		cout<<"\n\n\n*****SISTEMA FICTÍCIO*****";
		cout<<"\nBEM VINDO AO MANUAL DO USUÁRIO DO MONEDA";
		cout<<"\n\nNosso sistema foi projetado para caixa em qualquer tipo de produto, nele contêm ";
		cout<<"\ninformações que ajudarão o usuário a organizar melhor seu serviço de atendimento em ";
		cout<<"\nvendas, compras e despesas.";
		cout<<"\n\nNosso sistema contém 6 opções para o usuário sendo: 1 - CADASTRO, 2 - CONSULTA, 3 - ";
		cout<<"\nVENDAS, 4  - ESTOQUE, 5 - RELATÓRIO, 6  - NF";
		cout<<"\n\n°1 - CADASTRO = Nesta escolha você terá mais 4 opções ";
		cout<<"\n\t1 - CLIENTE - Onde poderá cadastrar os clientes que compram a prazo, ";
		cout<<"\n\tfornecendo dados: nome, CPF, telefone, endereço.";
		cout<<"\n\t2 - PRODUTO  - Aqui irá cadastrar produtos adquiridos para o seu comércio, ";
		cout<<"\n\tfornecendo: nome do produto, lote, validade, marca.";
		cout<<"\n\t3 - FORNECEDOR - Aqui irá cadastrar empresas que fornecem os produtos para ";
		cout<<"\n\tseu comércio, fornecendo: nome, CNPJ.";
		cout<<"\n\t4 - DESPESAS  - Nela poderá cadastrar gastos mensais: água, luz, internet etc...";
		cout<<"\n\n°2 - CONSULTA = Nesta escolha você terá mais 4 opções ";
		cout<<"\n\t1 - CLIENTE - Onde irá consultar os seus clientes cadastrados pelo CPF.";
		cout<<"\n\t2 - PRODUTO  - Onde irá consultar os seus produtos cadastrados pelo: nome do ";
		cout<<"\n\tproduto.";
		cout<<"\n\t3 - FORNECEDOR - Onde irá consultar os seus fornecedores cadastrados pelo: ";
		cout<<"\n\tnome, CNPJ.";
		cout<<"\n\t4 - DESPESAS  - Onde irá consultar os seus despesas cadastradas.";
		cout<<"\n\n°3 - VENDAS = Nesta opção irá optar a forma de pagamento";
		cout<<"\n\t1 - A VISTA  - Escolhendo esta forma de pagamento o cliente poderá pagar com ";
		cout<<"\n\tdinheiro ou cartão.";
		cout<<"\n\t2 - A PRAZO - Esta forma de pagamento é somente para clientes cadastrados no ";
		cout<<"\n\tcomércio";	
		cout<<"\n\n°4 - ESTOQUE = Nesta opção estará todos os produtos cadastrados no comércio que ";
		cout<<"\nestão em estoque.";
		cout<<"\n\n°5 - RELATÓRIO = Terá 2 opções poderá consultar os relatórios da sua empresa";
		cout<<"\n\t1 - VENDAS = Que irá constar os demonstrativos de vendas diárias e mensais. ";
		cout<<"\n\t2 - COMPRAS = Irão constar os demonstrativos de compras para o comércio.";
		cout<<"\n\n°6 - NF = Nesta opção poderá gerar um nota fiscal caso cliente deseje.";
		cout<<"\n\n\nMONEDA ";
		cout<<"\nVERSÃO 3.0 ";
		cout<<"\nCRIADO POR SAM TECNOLOGY";
		cout<<"\n\nCONTATO: usuário.prolapso@gmail.com ";
		cout<<"\n\tTel: 3531 - 2222\n\n\n";
	}
	};
	
	int main(){
	
	setlocale(LC_ALL, "Portuguese");
	Market d;
	int n;
		
	do {
		
		cout<<"\nSEJA BEM VINDO AO MONEDA";
		cout<<"\nESCOLHA UMA OPÇÃO";
		cout<<"\n1 - CADASTRO\t2 - CONSULTA\t3 - VENDAS\t4 - ESTOQUE\t5 - RELATORIO\t6 - NF\t7 - AJUDA :";
		cin>>n;
		system ("cls");
		
		switch (n){
		
		case 1:d.cadastro();break;
		case 2:d.consulta();break;
		case 3:d.vendas();break;
		case 4:d.estoque();break;
		case 5:d.relatorio();break;
		case 6:d.nf();break;
		case 7:d.ajuda();break;
		
		}
		
	cout<<"\n\n1 - MENU INCIAL\t\t\t2 - SAIR :";
	cin>>n;
	system ("cls");
	}
	while (n == 1);
	
	
	system ("pause");
	}

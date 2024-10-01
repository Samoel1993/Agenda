public class Funcionario extends Pessoa{
    private String matricula;
    private double salario;


    public Funcionario(String cpf, String nome, int tipo, Contato contato, String matricula, double salario){
        super(cpf, nome, tipo, contato);
        this.matricula = matricula;
        this.salario = salario;
    }

    public void setMatricula(String matricula){
        this.matricula = matricula;
    }

    public String getMatricula(){
        return matricula;
    }

    public void setSalario(double salario){
        this.salario = salario;
    }

    public double getSalario(){
        return salario;
    }


    @Override
    public String mostraDados() {
        return "Matricula = " + getMatricula() + "| CPF = " + getCpf() + " | nome = "+ getNome() + " | Tipo = funcionario" + " | celular = " + getContato().getCelular()+ "| e-mail = " + getContato().getEmail()+ " | Salario = "+ getSalario();
    }


}

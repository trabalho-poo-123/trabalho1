# trabalho1
trabalho poo

jogomemoriamain:

package jogomemoriamain;

import telas.telaprinc;

public class jogo {

    public static void main(String[] args) {
        telaprinc tela = new telaprinc();
    }
    
}


regras:

 package regras;

import javax.swing.JButton;

public class cartas {
    private JButton carta;
    private Boolean carta_select;
    
    public JButton getCarta() {
        return carta;
    }
    
    public void setCarta(JButton carta){
        this.carta = carta;
    }
    
    public Boolean getCarta_select(){
        return carta_select;
    }
    
    public void setCarta_select(Boolean carta_select){
        this.carta_select = carta_select;
    }

}


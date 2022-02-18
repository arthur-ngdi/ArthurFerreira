<h2> Hey, buddy! I'm Arthur Ferreira!</h2>
<img align='right' src="https://media.giphy.com/media/ule4vhcY1xEKQ/giphy.gif" width="230">
<p>Student of Computer Enginneering at  <em><a href="https://inatel.br/home/" target="_blank">Instituto Nacional de Telecomunicações</a></em>, Eletronics Technician with emphasis in Telecomunications at <em><a href="https://www.etefmc.com.br" target="_blank">Escola Técnica de Eletrônica "Francisco Moreira da Costa"</a></em> and trying Hard to be a Web Developer.
</p></br>

[![Linkedin: Arthur Ferreira](https://img.shields.io/badge/-Arthur%20Ferreira%20Silva-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ArthurFerreiraSilva/)]( www.linkedin.com/in/ArthurFerreiraSilva)
[![GitHub Arthur Ferreira](https://img.shields.io/github/followers/arthur-ngdi?label=follow&style=social)](https://github.com/arthur-ngdi)


### A little more about me...  

``` Java

import java.util.ArrayList;

public class Arthur extends Developer{

    private int energy;
    ArrayList<String> knowledge = new ArrayList<String>();

    public Arthur(){

        knowledge.add("Java");
        knowledge.add("SQL");
        knowledge.add("DataBase");
        knowledge.add("Python") ;
        knowledge.add("JavaScript");
        knowledge.add("C++");
        knowledge.add("C");
        knowledge.add("Arduino");
        knowledge.add("HTML5");
        knowledge.add("CSS3");
        knowledge.add("MQTT Protocol");
        knowledge.add("GIT");
}

    public ArrayList getKnowledge() {
        return knowledge;
    }

    public void setknowledge(String curso) {
        System.out.println("Alura?");
        knowledge.add(curso);
    }

    public int getEnergy() {
        return energy;
    }

    public void setEnergy(int energy) {
        this.energy = energy;
    }

    public void drinkCoffee (){
        if(this.energy < 100) {
            System.out.print("let's go!");
            this.energy = 100;
        } else {
            System.out.print("I'm not in need of energy, but every time is a good time for a little coffee!");
        }
    }
}

```

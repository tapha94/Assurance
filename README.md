# Assurance
Mes premiers modifications
2 

package stringDemo;

public class StringDemo {

    public static void main(String[] args) {
        // Déclarez et créez une chaîne de caractères
        String shockingSentence="The Java String type actually is a class, not a simple type!";
        // Faites-le savoir
        System.out.println(shockingSentence.toUpperCase());
        // Inversez-le
        System.out.println(shockingSentence.replace("simple","primitive"));
    }
    
}


3 

package cleanHello;

/** Ceci est une implémentation du message traditionnel "Hello world!"
* @author L'équipe Education d'OpenClassrooms
*/
public class CleanWorld {

    /** Le programme commence ici */
    public static void main(String[] args) {
        sayHelloTo("world");
    }

    /** affiche le message "hello" au destinataire fourni
    *
    * @param recipient
    */
    private static void sayHelloTo(String recipient) {
        System.out.println("Hello " + recipient);
    }

}

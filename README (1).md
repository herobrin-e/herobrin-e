``` java
import galaxy.earth.herobrine;
public class HeroBrine{

    static void languages(){
        String languages = {"Java","TypeScript","C++","Python"};
        for(byte control = 0; control <= languages.length; control++){
            System.out.println("I code in :" + languages[0]);
        }
    }
    static void frameworks(){
        String frameworks = {"Next.JS","Spring Boot","Arduino","LightGL","SciPy","NumPy","Pandas","OpenCV","TensorFlow","PyTorch"};
        for(byte control = 0; control <= frameworks.length; control++){
            System.out.println("I write in " + frameworks[0] + " framework");
        }
    }
    static void about(){
        String goals = {"Open Source"};
        for(byte control = 0; control <= goals.length; control++){
            System.out.println("Code to contribute to " + goals[0] + " framework");
        }
    }
}
```
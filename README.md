# modelmarks987
all simple codes in java available to choose and use 
import java.io.File;
public class filemng {

    public static void main(String[] args) {
        // Get the current directory
        String currentDir = System.getProperty("user.dir");

        // Create a File object for the current directory
        File dir = new File(currentDir);

        // Get a list of all files and directories in the current directory
        String[] files = dir.list();

        // Print the names of all files and directories
        for (String file : files) {
            System.out.println(file);
        }
    }
}


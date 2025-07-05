public class CompanyCity {
    public static void main(String[] args) {
        if (args.length != 2) {
            System.out.println("Please provide exactly two arguments.");
            return;
        }
        String companyName = args[0];
        String location = args[1];
        String output = companyName + "Technologies" + location;
        System.out.println(output);
      }
    }
        


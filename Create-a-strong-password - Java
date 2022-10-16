

import java.util.Random;
public class Pass {

    public static void main(String[] args) {
           Pass();
          
   }

   public static void Pass(){
   
      String CH = "ABCDEFGHIJKLMNOPQRSTUVWXYZ",
      ch = CH.toLowerCase(),sy = "!@#$_.",
      nums = "1234567890",
      pa = ch + CH + sy + nums;
      Random random = new Random();
      char[] password = new char[12];
      password[0] = ch.charAt(random.nextInt(ch.length()));
      password[1] = CH.charAt(random.nextInt(CH.length()));
      password[2] = sy.charAt(random.nextInt(sy.length()));
      password[3] = nums.charAt(random.nextInt(nums.length()));
      for(int i = 4; i< 12 ; i++) {
      password[i] = pa.charAt(random.nextInt(pa.length()));
      }
       System.out.println(password);
   
   
   }

}
